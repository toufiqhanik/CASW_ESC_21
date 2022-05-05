# CASW_ESC_21
Side Channel &amp; Fault Injection Attacks on CSAW’21 ESC Challenge Sets

This manuscript deals with the vulnerability of
the problems provided by the CSAW 2021 Embedded Security
Challenge as a red team, concentrating on side-channel and
fault injection attacks. We address the presented challenges and
their pitfalls in this paper. The technical approaches that can be
utilized to leak confidential information were also explored, as
well as potential mitigation for such vulnerabilities. Our UMBCSECRETS
team was able to crack all 10 given challenges using
computational approaches. This paper breaks down technical
specifics of the attacks into simple stages.

Index Terms—CSAW, Embedded Security Challenge, Side
Channel Attacks (SCA), Fault Injection Attacks (FIA)


The 2021 Cyber Security Awareness Week (CSAW) Embedded
Systems Challenge [1], [2] focuses on vulnerability
of computer programs written in C programming language
running on an micro-controller architecture. 3 sets of problems
with 10 challenges in total are provided for the red team
to analyze the vulnerability and perform potential attacks
to extract the secret information from the given operating
programs. The main assumption is that if these programs are
running on a system, how an attacker can manipulate the
system through side channel analysis or fault injection to leak
the hidden messages.

As a red team, different attacks have been launched on all
the challenges provided by our UMBC-SECRETS team. We
realized that some of running operations are clearly visible
from the power traces. The amplitudes of the power traces
may represent how many bits are being processed inside, or
which particular instruction is running. Also, some information
about the execution time can be leaked from power traces.
Such information can help in uncovering the secrets. Finally,
although the fault injection function of the given board does
not have much flexibility, it is still quite effective in attacking
some of the given challenges.
