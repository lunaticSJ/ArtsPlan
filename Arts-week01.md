1.Algorithm
Multiply Strings
Given two non-negative integers num1 and num2 represented as strings, return the product of num1 and num2, also represented as a string.

Example 1:

Input: num1 = "2", num2 = "3"
Output: "6"
Example 2:

Input: num1 = "123", num2 = "456"
Output: "56088"

2.Review

推荐即将发行(2019-11-4)的新书，作者Brendan Gregg是Netflix的高级性能工程师，也是bpf（ebpf）的主要贡献者。

BPF是动态跟踪的代表，排查问题的利器。

本书主要讲解使用BPF进行各种场景的性能分析，覆盖CPU、memory、disks、file system、networking、 不同开发语言、应用如mysql、容器、虚拟化等。

BPF开发很繁琐，本书重点推荐高级语言前端工具BCC和bpftrace，bpftrace已经在Netflix、Facebook和Shopify等公司用于生产分析。

这本书号称是Linux可观察性新时代的开始，在生产中拥有轻松查看任何东西的能力。

3.Tips
Golang中 int转string，主要有三种方法:

a. strconv.Itoa, str := strconv.Itoa(i)
b. strconv.FormatInt, str := strconv.FormatInt(i, 10)
c. fmt.Sprintf,  str := fmt.Sprintf("%d", i)


4.Share
