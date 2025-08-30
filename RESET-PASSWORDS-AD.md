# Reset Passwords in Active Directory (AD)

This guide explains how to reset user passwords in **Active Directory Users and Computers (ADUC)**.

> **Goal:** Reset a user’s password and optionally unlock their account.

---

## 1) Open Active Directory Users & Computers

1. Go to the **Search bar** on Windows Server.
2. Type **Active Directory Users and Computers** and open it.
3. Expand your **domain** and navigate to the **Users** folder (or relevant OU).

---

## 2) Select the User

1. Find the account you need to reset.
2. Right‑click the user account.
3. Select **Reset Password**.

---

## 3) Enter New Password

1. Enter the **new secure password**.
2. (Optional) Select **Unlock the user’s account** if the account is locked.
3. Click **OK**.

---

## 4) Confirmation

- A message will appear confirming the password was changed.
- Click **OK** to finish.

---

## Best Practices

- Use **strong passwords** that meet complexity requirements (uppercase, lowercase, numbers, symbols).
- Consider enabling **"User must change password at next logon"** if this is a standard reset for security purposes.
- If this is a repeated reset for the same user, check for account compromise.

---

## Credits

Created by **Zahir Haynes** as part of AD administration practice.
