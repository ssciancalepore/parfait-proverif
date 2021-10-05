This is the code used to verify some of the security properties of the PARFAIT protocol, presented in the paper "PARFAIT: Privacy-Preserving, Secure, and Low-Delay Service Access in Fog-enabled IoT Ecosystems".

The folder contains two tests.

- test1.pv 
The test is meant to verify the authentication of the Gateway to the AtA in the Cloud and the Fog node, as well as the secrecy of the identity 's_n' from eavesdroppers.

- test2.pv
The test is meant to verify that, even if the key of the GW-Fog communication link is leaked and public, the identity s_n still remains secret.

To run the scripts:
- compress the archive
- go to ./proverif2.02pl1/
- for the test1, run ./proverif.exe /docs/test1.pv 
- for the test2, run ./proverif.exe /docs/test2.pv 

For any questions, contact s.sciancalepore@tue.nl

Enjoy with the code!

