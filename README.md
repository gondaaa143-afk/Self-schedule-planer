# Self Schedule Planner — Build Ready

This project includes a GitHub Actions workflow that builds the Android debug APK automatically.

## Phone-only build steps

1. Create a free GitHub account.
2. Create a new repository, e.g. `SelfSchedulePlanner`.
3. Upload the contents of this ZIP to the repository (not the ZIP itself).
4. Open the repository's **Actions** tab.
5. Open **Build Android APK**.
6. Tap **Run workflow** if it is not already running.
7. After the workflow finishes, open the completed run.
8. Under **Artifacts**, download `SelfSchedulePlanner-debug`.
9. Extract it and install `app-debug.apk` on your Android phone.

The APK is a debug build for personal testing. The Friends feature in this MVP is UI/demo only and does not yet provide real online accounts or synchronization.
