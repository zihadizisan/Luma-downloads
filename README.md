# Luma 0.4.0 — free Windows beta

A little company. A little progress.

Luma is an offline Windows study timer with a small desktop companion. Name a lesson, choose 25 or 45 minutes, and complete the session to add its focus time to your history. You can pause and resume. Optional notes let you write a next step and choose Continue when you return; Luma does not reopen your course or create automatic bookmarks.

## Download status

This is the official binary download repository for Luma. The 0.4.0 installer is being prepared for publication; it is not downloadable here yet. The app's source repository remains private.

The installer is Luma-0.4.0-Setup.exe. It is about 159.6 MB and **unsigned**. A checksum verifies file identity; it is not a safety guarantee. Use a PC on which you have installation permission, and stop if Windows or your device policy raises a concern you cannot resolve. The package targets Windows x64; a minimum Windows version/build has not been qualified. Native ARM64, x86, Mac, Linux, mobile and web versions are not provided.

## Install and use

Quit Luma or an older FocusPet before running setup. Setup installs for your Windows account. Launch Luma, enter a lesson name and choose a session length. Only a completed full focus session earns credit; paused time, unfinished sessions and breaks do not. Closing the window normally leaves the timer in the tray. Choose Quit Luma to exit and save/pause an active session.

The study-day display uses 6 am–6 am in Asia/Dhaka, even if Windows uses another timezone. History is retained when the display rolls over.

## Local data

The app works offline without an account, analytics service or automatic uploads. History/settings live under `%LOCALAPPDATA%\FocusPet`. Database, backup and export files contain readable lesson names and notes. Your own sync software may upload a separately selected backup folder. Uninstall keeps local history; a later manual removal of that data folder and any separate exports/backups is your choice. Keep any backup you want before deleting data. Restore replaces history rather than merging it.

No study enrollment is open in this release candidate. Trying the app does not consent to research, upload history or subscribe you to messages. A future optional study must describe its separate fields, contact route and consent before collection. Do not upload your database or lesson notes to an issue.

## Beta and updates

This is a free beta; future paid packaging is undecided. There is no automatic updater. A later installer, if supplied, is installed manually after quitting the app. No future release, cloud service, indefinite compatibility or continuing support is promised. After publication, public release information can be checked in the download repository; that is a place to check manually, not an automatic-notice subscription.

The founder's study-support window, reply capacity and report-return route will be specified separately before any study opens. No immediate response or perpetual support is offered by this candidate.

## Verification record

The 20 October 2026 installer rehash matches the saved 0.4.0 release manifest. The current ASAR payload matches the saved packaged-test target. Saved 19 October checks report102 unit tests and12 packaged feature checks, including manual notes and continuation, using isolated synthetic data and controlled clocks/file dialogs. These are not customer results or a fresh real-profile install/upgrade/uninstall qualification. Native notifications, physical hotkeys/topmost behavior and a minimum supported Windows build remain outside this claim.

Distribution contains only the compiled installer, this README and a SHA256 file. It contains no product source archive, personal study history or contact list. GitHub-generated source archives contain this download repository's documentation, not the Luma application source. The older private v1/0.3.4 release is a different version.