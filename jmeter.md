**Setting up Load Tests in Jmeter**

```agsl

1.Start JMETER
2.Create a Test Plan
3.Create a Thread Group (Users)
  
  Thread group users are the number of users that will be doing a load test
4.Adding a Sampler (HTTP Sampler)

  Where we specify the endpoints to be tested, example,
  
  https://valleyroad.citam.org/live-service-today/
  
  We can specify our test samplers to be GET, POST, ETC.
  
5.Adding Listeners.

Listeners help us in viewing the load test results.

6.Running the Test

```
![Screenshot 2023-11-08 at 12.14.04.png](..%2F..%2FScreenshot%202023-11-08%20at%2012.14.04.png)

**Thread Group**

```agsl

A thread group is like a small block of what i am testing.

Most importatnly we set the number of users and the requests per second.
```
**JMETER Listeners**

```agsl
Are used to view the results/Performance of a Test

Types of listeners:

(a)View Results in Table.
(b)View Results Tree
(c)Aggregate Report. (Has got a lot of tabular details)
(d)Graph Results.
(e)Summary Report. (Has a little lesser details than the summary report)
(f)Simple Data Writer. (We have an Option to send results to a file)

Latency -->Time to first Byte.
ThroughPut-->Number of requests per minute

```

**Assertions**

```agsl
Assertions  = Checks the request and the Response.

1.Response Assertion
2.Duration Assertion
3.Size Assertion
4.HTML Assertion
5.XML JSON Assertion
6.XPATH Assertion

```

![Screenshot 2023-11-08 at 16.55.25.png](..%2F..%2FScreenshot%202023-11-08%20at%2016.55.25.png)