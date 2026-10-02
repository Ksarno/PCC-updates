# PCC 1.0.7 Burn manifest modification

The accompanying Burn-application.manifest is the complete modified RT_MANIFEST XML used in PCC Setup 1.0.7. The requestedExecutionLevel is changed from asInvoker to requireAdministrator before signing. The optional XML declaration is removed and trailing spaces preserve the original resource length, so Burn container offsets do not move. Burn executable code is unchanged.

The modified WiX XML materials are supplied under MS-RL (WIX-MSRL-LICENSE.txt). The pinned complete WiX 3.14.1 source archive accompanies the release. The PCC native extension is original separate code.
