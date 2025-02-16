<!-- markdownlint-disable MD033 MD041 -->
<p align="center">
<a href="https://ctflearn.com/"><img alt="https://ctflearn.com/" src="images/logo.png" width="90" height="90"></a>
</p>
<!-- markdownlint-enable MD033 -->

# CTFLEARN

## Basic Injection

See if you can leak the whole database using what you know about SQL Injections. [link](https://web.ctflearn.com/web4/)

Don't know where to begin? Check out CTFlearn's [SQL Injection Lab](https://ctflearn.com/lab/sql-injection-part-1)

### Solution

Vào thử thách, chúng ta có một trang web sau:

![image](images/basic-injection/image-1.png)

Có thể thấy đây là một thử thách liên quan tới lỗ hổng SQL Injection. Và chúng ta sẽ lấy flag thành công với một payload cơ bản `' OR 1=1#`:

![image](images/basic-injection/image-2.png)

### Flag

`CTFlearn{th4t_is_why_you_n33d_to_sanitiz3_inputs}`
