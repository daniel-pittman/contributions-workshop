# Flutter Todo App — Workshop

A Flutter todo app with a few bugs hiding in it. Your job is to find them and fix them!

This workshop is designed to give you hands-on experience with the **open source contribution workflow** used by real projects on GitHub.

---

## The App

A simple todo list where you can add tasks, mark them complete, and delete them.

**Something feels off though...** There are **4 bugs** in `lib/main.dart`. Each one is filed as a GitHub Issue. Pick one, fix it, and open a Pull Request!

---

## Getting Started

### Prerequisites

- [Flutter SDK](https://docs.flutter.dev/get-started/install) installed
- A GitHub account
- Git installed

### Run the app

```bash
flutter pub get
flutter run
```

Play around with the app and see if you can spot the bugs before reading the issues.

---

## Contribution Workflow

This is the same workflow used when contributing to any open source project on GitHub.

### 1. Fork the repo

Click **Fork** at the top-right of this GitHub page. This creates your own copy of the repo under your account.

### 2. Clone your fork

```bash
git clone https://github.com/<your-username>/todo_workshop.git
cd todo_workshop
```

### 3. Create a branch for your fix

Name your branch something descriptive:

```bash
git checkout -b fix/delete-wrong-task
```

### 4. Pick an issue

Go to the **Issues** tab on GitHub and find a bug that hasn't been claimed yet. Leave a comment saying you're working on it so others know.

### 5. Fix the bug

All bugs are in `lib/main.dart`. Read the issue description carefully — it tells you what you should *observe*, not how to fix it. You'll need to dig into the code yourself.

### 6. Test your fix

Run the app and confirm the bug is gone:

```bash
flutter run
```

### 7. Commit your change

```bash
git add lib/main.dart
git commit -m "Fix: <short description of what you fixed>"
```

### 8. Push to your fork

```bash
git push origin fix/delete-wrong-task
```

### 9. Open a Pull Request

Go to your fork on GitHub and click **Compare & pull request**. In your PR description:

- Reference the issue you fixed (e.g., `Closes #2`)
- Briefly explain what the bug was and what you changed

### 10. Review & merge

Your PR will be reviewed. Once approved, it gets merged into the main repo — your contribution is in!

---

## Tips

- Each bug is only a line or two to fix — no need to rewrite anything
- Run `flutter run` often to verify your changes
- If you're stuck, re-read the issue and trace through the code step by step
- Ask for help — that's what open source communities do

---

## Project Structure

```
lib/
  main.dart   ← all the app code lives here
```

All bugs are in `lib/main.dart`. Happy hunting!
