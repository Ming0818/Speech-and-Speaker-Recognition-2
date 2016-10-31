# Speech-and-Speaker-Recognition

Abstract:

With several advancements in technology we are not far away from a future where all devices are connected and interact
with each other through the concept of Internet of Things. One of the key concerns in realizing a solution that will be
adopted worldwide is security. In particular, secure access to data and services is an important problem. Through this
project I propose to address the security problem from a biometrics stand point.
Voice biometrics is emerging as an interesting and unobtrusive way to address the issue of security and perform user
authentication while providing improved user experience at the same time. The existence of several commercial solutions
such as Nuance voice biometrics, Voice Biometrics Group, Authentify and VoiceVault and many more provide good
support to this fact. Bank transactions, access to database, physical access to special zones, improving general user
experience by removing the requirement of a password, or uses in forensic applications are all important applications of
a VB systems.

Through this project, a voice based biometric systems that uses both language and speaker ID information for
authentication is built. Previous research topics have concentrated on performing only speaker recognition for a voice
based biometric system. Efforts will be directed towards suppressing the effects of language of a speaker in the SID
models. Efforts to perform efficient LID will also be done in parallel. However, I propose to add the language spoken also
as another security parameter apart from the speaker ID.

Idea:

The idea is to employ a two-fold approach. In the first step language identification is performed to identify the language
spoken. Concurrently speaker verification is performed to identify who was speaking on the given utterance (Speaker ID).
The result of both LID and SID is fed into a decision maker which checks for both the LID and SID result before giving access.

Results and Future work:

Based on a sample training/testing data, the system’s results for each speaker will show how a two-fold system provides
added security to perform authentication. However, the VB system is now dependent on good performance for both LID
and SID. Even if one fails, access will be denied. Although this can be seen as providing tighter security, it can sometime
lead to user inconvenience. Hence for future work a dynamic system can be built where depending on the speech uttered
by the speaker, the requirement of LID can be relaxed for low priority and lower risk transactions and applications.
However, if high risk transactions are performed then both LID and SID can be used for added security. Also a technique
that handles different languages in the same training speech could be developed to improve the performance of the LID.
