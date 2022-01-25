# Authenticated-RCE-CuppaCMS
CuppaCMS is vulnerable to Authenticated Remote Code Execution. \
An authenticated user can control both parameters (action and function) from "/api/index.php". \
The vulnerability can be exploited using POST method. \
Except action and function parameter we can add any parameter because its checking only parameter value not parameter name.

![RCE_Cuppa-1](https://user-images.githubusercontent.com/10436828/151036100-2ab0517a-eee2-42e2-8c67-597c4a890d63.png)
![RCE_Cuppa-2](https://user-images.githubusercontent.com/10436828/151036105-653f8ad6-71b0-4099-aea8-29b0cbb51744.png)

Issue submitted: https://github.com/CuppaCMS/CuppaCMS/issues/22
