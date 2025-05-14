# Medical-Chatbot
Always Show Hidden Files (permanently)
টার্মিনালে এই কমান্ডটা চালাও:
bash
defaults write com.apple.finder AppleShowAllFiles TRUE && killall Finder

✅ যদি তোমার Mac-এ VS Code ইনস্টল করা থাকে:
🔹 Terminal থেকে পুরো প্রজেক্ট ওপেন করতে:
bash
code .
এখানে code মানে Visual Studio Code
. মানে এই ফোল্ডার (current directory)

🔸 যদি কমান্ড code কাজ না করে, তাহলে করো এইটা একবার:
Step 1: VS Code ওপেন করো (GUI দিয়ে)
Step 2: Menu ➝ Command Palette খুলো:

css
Copy
Edit
⇧ Shift + ⌘ Command + P
Step 3: লিখো:

bash
Shell Command: Install 'code' command in PATH
Step 4: তাতে ক্লিক করো ✅

এখন থেকে code . কমান্ড কাজ করবে!