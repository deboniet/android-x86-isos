Below is more information about what I do in relation to the Android-x86 project. If you want the ISOs, they are hosted on [my Internet Archive profile](https://archive.org/details/@deboniet).

[Android 11 ISOs](https://archive.org/details/androidx86-11-isos)\
[Android 10 ISOs](https://archive.org/details/androidx86-10-isos)

[Common errors in the ISOs](https://github.com/deboniet/android-x86-isos/tree/main#common-errors-in-the-isos)

# What is Android-x86?

It's an open source project that ports Android to the x86 arquitecture so it can be executed in the computers that have that CPU arquitecure. The project is not mine. This repository it's just a link for the ISOs I built, and a memo of the the things I'm doing to archive the versions that are not in a ISO format.

# Why did you create this repository?

First, there are no official Android 10 and Android 11 ISOs from the developers of the project. Secondly, in the summer of 2024, OSDN servers went down for long periods of time. Right now, it's not possible to even connect to their servers. I thought that archiving those versions it's a good way of preserving that part of the Android-x86 project.

My ISOs are the result of my compilations, but you can also compile it by yourself using [my script](https://github.com/deboniet/scripts-bash/blob/main/androidx86build.sh), or you can follow [the outdated and not working official instructions](https://www.android-x86.org/source.html).

# How was the ISOs done?

Based on official instructions. The compilation options and other information are the default ones, and can be viewed on **system/build.prop** inside the ISOs file systems.

# How do I get the ISOs?

The ISOs are on Internet Archive, an organization that preserve the Internet. I think it's the best place to put this.

# Which versions did you archive?

All targets of Android 10 and 11 in x86 and x86_64 architectures.

# Please do this, please do that, please do it for me...

1. Search on the Internet, look for information, and try to do it yourself. The magic of the free and open source software is that knowing how it works, you can do whatever you want with it, and above that, that the collaboration between us makes the product even better.
2. If that doesn't give any result, ask someone. It's okey to ask, and if you ask me, I will try to help you. But, please if you do, be respectful and remember that this is a personal project and that I'm not a slave of anyone, not even working for anyone in particular.
3. If you need to ask something in private, do it by e-mail, it's in my profile. If you need to share something related to my repositories that it's of public interest, open an issue. Doing this will help to solve issues faster.
4. If the above is not respected, I-WILL-NOT-HELP-YOU. And I'm very clear about this. Be respectful with everybody, even on the Internet.

# <ins>Common errors in the ISOs</ins>
# 1. When I run the ISOs nothing appears on screen, what can I do?

When Grub menu appears follow the next steps:

1. Press the key *E*
2. Add the parameter *nomodeset* to the line that starts with *linux*
3. Press the key *F10*
4. The Android boot screen should appear and the ISO will boot properly.
