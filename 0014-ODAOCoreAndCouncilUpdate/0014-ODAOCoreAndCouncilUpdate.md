# 0014-ODAOCoreAndCouncilUpdate

- Status: Proposed
- Authors: Optim Labs

## Context

With the launch of OADA it is requisite that the ODAO's governance be directly connected to the update authority of the system. As such, we update ODAO Core, a branch of ODAO, as an Optim Labs + ODAO Members multisig for the purposes of conducting updates to the system without a single point of failure. Following passing of the proposal, move the update authority to the wallet

Furthremore, we update the ODAO Council, removing one member (inactive), replacing with two, and changing the consensus to a 5/9 from 4/8 to remove unnecessary potential for unresovable conflict. 

## Proposal

### ODAO Core Update

We propose the instantiation of the address addr1xx5nfsucfqj8uzsedwjhk7yq5sgwqc2ljlyl9c89tguhgk34h7m0f496nec0xrunrapufn9m3vrwzw0p7sp4jjn8swxsg5pq9x, as the main multisignature delegate of ODAO power to update OADA, to only use the power when ODAO Proposal passes with no autonomy unto itself other than the unspecified parts of the proposals. The address is derived from the multisignature native script:

- 2/2 (ODAO Core)
    - 1/3 (Optim Labs)
        - addr1q8fh7ws9ts208n6tjm8hzvx7wudehasakkxyrfjuxwpkmtfurl3593h9qsnnl4ql6cqlx54ayj4260rh5fu39j4z9zhqack0j3
        - addr1qygglztxdrteq8ulum5fggcc6zcpaehvgxg4klskf33hxzfaxd6wtnpdzysh6msh07t6yrpsn8wtcjnt8gtx5e8ef0mqhtexys
        - addr1q8ga69daxltdps2fjy0tjqzn372dqacmqm5j6xxysmk0tr8z9yjwms5qqhxke0w604wuqq0wqyq28tqnur4nfw9cay9sqhp7l7
    - 3/7 (ODAO)
        - addr1qxplgjyc27mnglvyc97drfz7gl652vrf6tnsletas4ecgq4u003f8hzqvjaxnydfljly7mkj7d84w0ds79aptd7vpwqq9amc9y
        - addr1qx6zda72xdj2ky25hhtykculgmpfmur4uce35jcmgk8kmjtlnyq39698lulm4gv3ktff3zz9tttfph5pz4cd840nj93saghqj5
        - addr1qys34kkns6jrfw26ydqay3ekgt9fpxfchg4vsqp9en2r3fppn66n8hkalfycp2yr6ajgw5gat9v2tjdhmrq3yhwxlkzsqs9hyz
        - addr1qxhfgrwd04pjmmyp272hel5ld4mpzkfd5z2q6hvhmzsa8xwf6k8u043rkty9ggferjg08mqyxulj7zzrw6nxrjr370wqecxugq
        - addr1q977rwuqz0hpfstn2dgudpm639wxd0kw6eds45e3vruvpqftvtafztg9w3xlrvuuf299we4vtyce8nnpcayelsr77dqsds4lg3
        - addr1q9tzngljztzee43zk9nfe48hnjcfhv3y8rehwfdkvvuvgt3ucmrg667ktz4zhmaadk3qtm0evzdt4xczja8jfjy3973scys9hj
        - addr1qyd2dq8pa6zjkwcf65jlke2sm9thlmaggytx0s7ktzydu8uk2l9dm3pzvlf3k54z2dlf8wf8hskzrpq03dhu8kpnag4qkgxv6s

The following ODAO members (in order) are members of the ODAO Core:
- Cakes
- Joynul
- Jamie of Ionia
- Noah
- InputEndorsers
- Klaus
- Cloud

### ODAO Council Update

The update removes Impala as an ODAO Council member, adding Noah and Artifex in here place.

We also move the consensus from 4/8 to 5/9 for greater resilience. 