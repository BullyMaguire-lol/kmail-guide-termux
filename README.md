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
<img width="1600" height="720" alt="1" src="https://github.com/user-attachments/assets/bdae9733-1522-49b8-9b3b-85b4ec991070" />

5. Keep the default wallet name (`kdewallet`) and click **OK**.
<img width="1600" height="720" alt="2" src="https://github.com/user-attachments/assets/f7a6c1b5-b325-4b72-9c0a-31dfeb3994ab" />

6. Select **Classic, blowfish encrypted file**, then click **Finish**.
<img width="1600" height="720" alt="3" src="https://github.com/user-attachments/assets/1ed18822-e078-489d-89e3-3d616b281d24" />

7. Create a password for the wallet.
<img width="1600" height="720" alt="4" src="https://github.com/user-attachments/assets/445a6c06-028c-484e-b13b-36ee27e29700" />

8. Log out of the Plasma session. **Do not skip this step.**
<img width="1600" height="720" alt="5" src="https://github.com/user-attachments/assets/89543b0d-5dc4-476b-ab96-13b356c06b1d" />

9. Start Plasma again:

   ```sh
   termux-x11 -xstartup startplasma-x11
   ```

10. Open **KMail**.
<img width="1600" height="720" alt="16" src="https://github.com/user-attachments/assets/17825ab5-6c30-4a08-95b7-bf275f1653ec" />

11. Enter your name and Gmail address, then click **Next**.
<img width="1600" height="720" alt="6" src="https://github.com/user-attachments/assets/07ae042d-eb31-4dae-96c8-609e6b7a43bf" />

12. If prompted about **Unified Mailboxes**, click **Cancel**.
<img width="1600" height="720" alt="17" src="https://github.com/user-attachments/assets/68a74b87-d7d1-4e12-a904-1253be8adcd4" />

13. Enter the KDE Wallet password you created earlier.
<img width="1600" height="720" alt="7" src="https://github.com/user-attachments/assets/ece1bb52-88e8-4391-a61e-fe0d0787bb15" />
<img width="1600" height="720" alt="8" src="https://github.com/user-attachments/assets/958ad461-cce1-4812-b1e1-058370817f23" />

14. If the browser opens automatically, continue with the Google sign-in.

15. If the browser does not open automatically, click **Previous**.
<img width="1600" height="720" alt="9" src="https://github.com/user-attachments/assets/97eb14ec-8e51-41b5-8f23-6cfeed458852" />

16. Click **Next** again.
<img width="1600" height="720" alt="10" src="https://github.com/user-attachments/assets/ce508ed4-a507-43f7-84d8-6a7b17d67a9c" />

17. Sign in to your Gmail account and complete the authorization.
<img width="1600" height="720" alt="11" src="https://github.com/user-attachments/assets/36cb3022-8a43-4eb4-8947-1974b7ff1a88" />
<img width="1600" height="720" alt="12" src="https://github.com/user-attachments/assets/d16b2234-cfcc-40c2-80f9-791961fccd7f" />

18. Return to KMail and click **Finish**.
<img width="1600" height="720" alt="13" src="https://github.com/user-attachments/assets/8925ae55-12b2-401b-a4bc-fa943e798377" />

19. Close KMail.
<img width="1600" height="720" alt="14" src="https://github.com/user-attachments/assets/83d85edb-95a1-496e-9b53-406d09586489" />

20. Open KMail again.
<img width="1600" height="720" alt="16" src="https://github.com/user-attachments/assets/17825ab5-6c30-4a08-95b7-bf275f1653ec" />

21. Click **Check Mail** to verify that your account has been configured successfully.
<img width="1600" height="720" alt="15" src="https://github.com/user-attachments/assets/42e42723-162b-4169-9b20-29fcf9268da3" />

## Related

Termux KMail package PR:
https://github.com/termux/termux-packages/pull/28403
