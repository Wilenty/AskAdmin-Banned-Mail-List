# AskAdmin - Banned Mail List (your e-mail on their black list)

At the outset. I've send an e-mail for all of the mentioned users with question if they allows to share this program (two weeks ago), and I don't get any negative response for about two weeks, so...

![e-mailSEND-2](https://user-images.githubusercontent.com/61757638/188722176-e72ecb18-c151-4214-b529-c742229c4af3.png)
![e-mailSEND-1](https://user-images.githubusercontent.com/61757638/188722229-59891bce-2501-476e-868f-8baa7ca4791f.png)

A word of explanation:
if you will decide to pay for AskAdmin program, and then you will stop doing it - your e-mail address will be added to the mentioned list in the title. Or, if they will thinks that you selling your own copy of the AskAdmin program - your e-mail will be added there too!

You have to place this program in the extracted AskAdmin location, where the "AskAdmin.exe" and/or "AskAdmin_x64.exe" exists.
This simple program executes the "AskAdmin.exe" or "AskAdmin_x64.exe" (with special/hidden command-line parameter prepared by AskAdmin owners) depends of your OS architecture.

After successfully execution you will see all e-mails banned by the AskAdmin owners:

![AskAdmin-BannedMailList-OK](https://user-images.githubusercontent.com/61757638/188722419-f9f765f9-b481-4f79-9f9f-230b7a4ce547.png)

So please report them to the police or to the relevant authorities in your country if you find your email address on their list, because otherwise they will never understand that they are doing something wrong that they shouldn't be doing at all (and they won't stop attacking me)....

Possible messages on executing:
1. Can't find AskAdmin.exe in the current location ("X:\\(...)")...

![AskAdmin-BannedMailList-2](https://user-images.githubusercontent.com/61757638/183537040-ac036c55-b181-48b9-b865-a26ea13450e0.png)

2. Can't find the AskAdmin window...

![AskAdmin-BannedMailList-1](https://user-images.githubusercontent.com/61757638/183537080-cf2af149-1e09-472b-bb8e-fbdc6e381f5f.png)

If you want to have your own full version of AskAdmin without any restrictions, I will suggest to you to use my "AutoIT extractor" from there: https://github.com/Wilenty/Universal-AutoIT-Extractor-and-De-obfuscator
and chande some strings in the extracted script:
```AutoIt
;Statically e-mail addresses written, line: 128
```
```AutoIt
; Cooent line 129 to skip the licese dialog:
;If $cmdline[0] = 0 Then a4860004103()
```
``AutoIt
; "registration" in line 132
Global $a0fe130460a = a1570004a1a()
;TO skip registartion:
Global $a0fe130460a = true
```
instead of pay for it for people who won't understand that they doing wrong (and they are angry at me)...

If someone will decide to create a class action, please also include the message wrote by the AskAmin owners from there:
https://wilenty.wixsite.com/softwarebywilenty/post/wtarkan-started-a-conversation-with-you-and-we-will-find-you

Greetings,
Wilenty
