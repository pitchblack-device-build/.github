# PitchBlack Recovery - One Build, One Phone, One Backup

![PitchBlack Recovery backup list for a single device](https://pitchblackrecovery.com/assets/images/Gradient-Red-Logo-1.png)

## Product Snapshot

PBRP is another maintained recovery tree. The useful question is whether your codename has a build for the Android version you are on. If it does, the workflow is ordinary: boot or flash that image, back up to storage you will not wipe, install one zip, reboot, and test. If it does not, stop. A build for a phone with a similar name is a good way to need the stock firmware you did not download first.

Backups that live only inside the phone are optimistic. A data wipe, a format, or a failed restore deletes the safety copy along with the problem. Move the backup to a computer before you wipe anything.

## Checks

| Item | Pass |
|---|---|
| Filename codename | Equals the phone |
| Free space off-device | Enough for the backup |
| Zip | Refuses the wrong device instead of being forced |
| Stock firmware | Already on the PC |
| Battery | High enough to finish |

1. Match the codename.
2. Boot the recovery.
3. Back up and copy it off.
4. Flash one package.
5. Boot the system before a second package.
6. Restore or return to stock if the first package was wrong.

[![Open PitchBlack Recovery](https://img.shields.io/badge/Open-PitchBlack-111827?style=for-the-badge&logo=android&logoColor=white)](https://palmiraaugeproqnv.github.io/.github/pitchblack-device-build)

## Fits

Owners of a device that has a PitchBlack build. A poor fit for unsupported phones and for account bypass. A poor fit when USB file transfer already solves the task. Recovery is for backup and install, not for browsing pictures.

## Requirements

| Item | Expectation |
|---|---|
| Device | The matching codename |
| PC | Somewhere to store the backup |
| Image | This device's build |
| Power | Charged |

## Fixes

It will not start. Wrong image. Do not try a second model.
Restore fails. The backup and the current ROM do not match.
A forced zip boot-loops. Flash stock. Forcing the assert was the mistake.
The backup is corrupt. The card was pulled early. Make another before you wipe.
You cannot find the codename. Look it up on the device before you download anything.

## Codename, Backup Off the Phone, Then One Zip

PitchBlack is safe only on the device the file was built for. Read the codename in the filename and on the phone. If they differ, do not boot the image "to see." A similar marketing name is how people need stock firmware they never downloaded. Put that stock package on the computer before you experiment.

Backups that stay on the data partition disappear when you wipe data. Copy the backup to a computer first. Flash one zip. Leave its assert alone. A forced package that boot-loops is fixed with the backup or with stock, not with a second phone's recovery. USB file transfer is enough when Android already starts and you only needed a photo.

- Codename matched
- Stock firmware already saved
- Backup copied off the phone
- One zip, assert intact
- Battery high enough to finish
- Restore skipped when the ROM and the backup disagree
- No account-bypass use on a device that is not yours

| Mistake | Result |
|---|---|
| Sibling model image | A phone that will not boot |
| Backup left on data | Gone after a wipe |
| Forced zip | Boot loop |
| Second zip immediately | Two causes if it fails |

Test the system once before you install anything else.

## Stock Package Before the Experiment

If the codename has no PitchBlack build, do not borrow one. Download stock firmware for this phone first, then boot the matching recovery. Copy the backup to a computer before you wipe. One zip, assert left on. A forced package is how the stock file becomes necessary. USB copy is enough when the system already boots and you only wanted a picture.

- Codename equal
- Stock file on the PC
- Backup moved off the phone
- Second zip only after a successful boot

## Naming Notes

pitchblack recovery, pbrp recovery, pitchblack device build, pbrp zip flash, pbrp backup restore, custom recovery codename, pitchblack stock fallback, pbrp android
