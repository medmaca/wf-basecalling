* Duplex mode cannot be used when calling modified bases. You must either run simplex basecalling with modified bases; or duplex calling without modified bases.
* Duplex mode with wf-basecalling is reliant on internal optimisations to organise input files for better duplex rates, which is not possible when using streaming basecalling; therefore duplex combined with the `--watch_path` option could lead to lower duplex rates than what would be achieved running the algorithm after sequencing is completed.