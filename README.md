# 🗳️ Online Voting System (C Language)

This is a **console-based Online Voting System** developed in C. It allows voters to securely cast their votes after verifying their identity through Aadhar ID, Name, and Date of Birth. The system prevents multiple voting attempts by the same user and provides real-time vote counts and result declarations.

## 💡 Key Features

- ✅ Voter identity verification using Aadhar ID, name, and birth date
- 🔁 Prevents duplicate voting
- 🗳️ Voting system with five predefined candidates
- 👨‍💼 Admin panel for live vote tracking (password-protected)
- 🏆 Displays winner based on highest vote count
- ❌ Auto-exit after 3 failed login attempts
- 📜 Clean menu-driven interface with animations using `Sleep`

## 👨‍💻 Technologies Used

- Language: **C**
- Platform: **Windows Console**
- Libraries: `stdio.h`, `stdlib.h`, `string.h`, `windows.h`

## 🔧 How to Compile and Run

1. **Save the code** to a file, e.g., `voting_system.c`

2. **Compile the code** using a C compiler:
   ```bash
   gcc voting_system.c -o voting_system
   
🧑‍⚖️ Admin Access
Access live vote counts

Password: 1722

Optionally terminate voting early with special password: 1234

🚫 Security & Limitations
Hardcoded voter credentials — no dynamic registration

Not encrypted or secured for production use

Windows-only due to use of windows.h and Sleep()

No file/database storage — data is lost on program exit

📜 License
This project is provided as-is for learning and demonstration purposes.
