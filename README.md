![Visitors](https://api.visitorbadge.io/api/visitors?path=https%3A%2F%2Fgithub.com%2ThantZinPhyo-OP%2Fngrok-rdp%2F&labelColor=%2314213d&countColor=%23e5e5e5&style=flat-square)

## Description
**What is RDP?**<br>
* RDP (Remote Desktop Protocol) is a network communications protocol developed by Microsoft, which allows users to connect to another computer from a remote location.

**How long does this RDP stay active?**<br>
* This RDP stays active for up to 6 hours.<br>

## How to use it?

#### First Step
1. Press the **fork** button  
2. Login or signup to ngrok: https://ngrok.com
3. Now visit here for token: https://dashboard.ngrok.com/auth/your-authtoken
You'll get token from here. It'll be needed to the next step.

#### Second Step
1. In your forked repo: **Go to Settings > Secrets > Action > New Repository Secret**
2. In the name section, enter this text: **NGROK_AUTH_TOKEN**
3. In the value section, enter the **ngrok token**
4. Then press **Add Secret**
5. Now go to **Action > AWS (Left Menu) > Run Workflow**
6. Refresh the page and go to **AWS > build** option
7. You'll get IP, Username & Password from **Connect to RDP** section.

#### Third Step
1. Search **Remote Desktop Connection** from Windows Start Menu and open.
2. Put IP without **tcp://** and enter Username & click **Connect**.
3. Later on, put the password for credential/auth.



## License
The content of this project itself is licensed under the [Creative Commons Attribution 3.0 Unported License](https://creativecommons.org/licenses/by/3.0/), and the underlying source code used to format and display that content is licensed under the [MIT License](LICENSE.md).
