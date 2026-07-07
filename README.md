# KMail Guide for Termux

This guide explains how to set up KMail on Termux.

## Setup

1. Start Plasma:

   ```sh
   termux-x11 -xstartup startplasma-x11
   ```

2. Open **System Settings**.

3. Go to **Security & Privacy → KDE Wallet**.

4. Click **New**.

5. Keep the default wallet name (`kdewallet`) and click **OK**.

6. Select **Classic, blowfish encrypted file**, then click **Finish**.

7. Create a password for the wallet.

8. Log out of the Plasma session. **Do not skip this step.**

9. Start Plasma again:

   ```sh
   termux-x11 -xstartup startplasma-x11
   ```

10. Open **KMail**.

11. Enter your name and Gmail address, then click **Next**.

12. If prompted about **Unified Mailboxes**, click **Cancel**.

13. Enter the KDE Wallet password you created earlier.

14. If the browser opens automatically, continue with the Google sign-in.

15. If the browser does not open automatically, click **Previous**.

16. Click **Next** again.

17. Sign in to your Gmail account and complete the authorization.

18. Return to KMail and click **Finish**.

19. Close KMail.

20. Open KMail again.

21. Click **Check Mail** to verify that your account has been configured successfully.
