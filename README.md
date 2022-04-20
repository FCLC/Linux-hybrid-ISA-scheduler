# Linux-hybrid-ISA-scheduler
Used as a staging ground for a hybrid scheduler capable of dealing with multiple different ISA's on the same host processor. 

Multiple approaches might be possible, but this is TBD









### Insipation and context 

As part of work in the CoreBoot project, the team at Dasharo were able to open up a bios for intel Alder Lake hybrid CPU's, which host both Golden cove Pcore's with AVX-512, as well as Gracemount E-cores which do not. 

Under normal circumstances, you would only be able to use either ecores+pcores in AVX2 mode, or disable the ecores and use AVX512 on the Pcores. 

https://twitter.com/FelixCLeClair/status/1516418881606279168?s=20&t=UgHzqJq6wuM7HRmwnHkMEA
