তোমার দেওয়া নির্দেশনাগুলো খুব সুন্দর ও কাজের! আমি এগুলো একটু সাজিয়ে দিচ্ছি যেন `README.md` ফাইলে সুন্দরভাবে দেখা যায় এবং ইউজাররা সহজে কপি-পেস্ট করে ব্যবহার করতে পারে। নিচে পুরো `README.md` এর একটি রেডি টেমপ্লেট দেওয়া হলো:

---

````markdown
# 🩺 Medical-Chatbot

এই প্রজেক্টটি চালাতে গেলে কিছু দরকারি টার্মিনাল কমান্ড এবং সেটআপ লাগবে। নিচে সব সুন্দরভাবে ব্যাখ্যা করা হলো ✅

---

## 🔍 Always Show Hidden Files on macOS

টার্মিনালে নিচের কমান্ডটি চালিয়ে চিরতরে হিডেন ফাইলগুলো দেখতে পাবে:

```bash
defaults write com.apple.finder AppleShowAllFiles TRUE && killall Finder
````

---

## 💻 VS Code দিয়ে প্রজেক্ট ওপেন করা

### ✅ যদি তোমার Mac-এ Visual Studio Code ইনস্টল করা থাকে:

টার্মিনাল থেকে এই কমান্ডটি চালাও:

```bash
code .
```

* `code` মানে Visual Studio Code
* `.` মানে বর্তমান ফোল্ডার (current directory)

### ⚠️ যদি `code` কমান্ড কাজ না করে, তাহলে:

1. Visual Studio Code ওপেন করো (GUI দিয়ে)
2. উপরের মেনু থেকে ➝ **View > Command Palette...** অথবা শর্টকাটঃ
   **⇧ Shift + ⌘ Command + P**
3. লিখোঃ

   ```
   Shell Command: Install 'code' command in PATH
   ```
4. যেই অপশন আসবে, তাতে ক্লিক করো ✅

এরপর থেকে `code .` কমান্ড কাজ করবে টার্মিনাল থেকে!


