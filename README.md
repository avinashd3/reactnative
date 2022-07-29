This project is for learning purpose.

Things to learns:
1) DRY coding.
2) React and React native concepts
3) Test driven development.
4) Increase productivity.
5) Learn DSA and its implementation.

<!-- Error -->
expo : File C:\Users\akash\AppData\Roaming\npm\expo.ps1 cannot be loaded because running scripts is  disabled on this system. For more 
information, see about_Execution_Policies at https:/go.microsoft.com/fwlink/?LinkID=135170.
At line:1 char:1
+ expo install react-native-gesture-handler react-native-reanimated
<!-- + ~~~~ -->
    + CategoryInfo          : SecurityError: (:) [], PSSecurityException
    + FullyQualifiedErrorId : UnauthorizedAccess
<!-- Error -->

<!-- Solution -->
Step 1: Open Windows PowerShell with Run as Administrator
.
Step 2: use (Get-ExecutionPolicy) this command on Windows PowerShell to see the execution policy
Step 3: Now we need to change this policy to allow the operation. Use this command to make it Unrestricted
.
Use (Set-ExecutionPolicy Unrestricted) this command
.
here you will get a prompt message and you should press 'Y' to change from Restricted to Unrestricted.
That’s it.
.
To ensure, you may check the execution policy by this
(Get-ExecutionPolicy) command again.
The possible output should be (Unrestricted)
<!-- Solution -->