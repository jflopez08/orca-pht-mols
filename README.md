# orca-pht-mols

##Commands to run an clean the Orca calculations:

`/home/flopez/orca/4.2.1/orca pht.inp --use-hwthread-cpus > pht.out &`
`/home/flopez/orca/4.2.1/orca p1r1.inp --use-hwthread-cpus > p1r1.out &`
`/home/flopez/orca/4.2.1/orca p1r2.inp --use-hwthread-cpus > p1r2.out &`
`/home/flopez/orca/4.2.1/orca p1r3.inp --use-hwthread-cpus > p1r3.out &`
`/home/flopez/orca/4.2.1/orca p2r1.inp --use-hwthread-cpus > p2r1.out &`
`/home/flopez/orca/4.2.1/orca p2r2.inp --use-hwthread-cpus > p2r2.out &`
`/home/flopez/orca/4.2.1/orca p2r3.inp --use-hwthread-cpus > p2r3.out &`

`ls | grep -xvP "p\d{1}r\d{1}.(xyz|inp|hess)" | xargs rm -rf`
`ls | grep -xvP "pht.(xyz|inp|hess)" | xargs rm -rf`
