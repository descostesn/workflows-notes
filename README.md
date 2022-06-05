# workflows-notes

## Publications

  * [Experiences with workflows for automating data-intensive bioinformatics](https://biologydirect.biomedcentral.com/articles/10.1186/s13062-015-0071-8)
  * [A review of bioinformatic pipeline frameworks](https://academic.oup.com/bib/article/18/3/530/2562749)
  * [The nf-core framework for community-curated bioinformatics pipelines](https://www.nature.com/articles/s41587-020-0439-x)
  * [DolphinNext: a distributed data processing platform for high throughput genomics](https://bmcgenomics.biomedcentral.com/articles/10.1186/s12864-020-6714-x)
  

## User interface solutions to design workflows:

- Chipster: https://chipster.csc.fi/manual/workflows.html
- Taverna: https://incubator.apache.org/projects/taverna.html
- Kepler: https://kepler-project.org/
- Galaxy: https://usegalaxy.eu/
- DolphinNext: https://dolphinnext.umassmed.edu/
- Sequana: https://academic.oup.com/bioinformatics/article/34/11/1934/4817647
- Gpcr-modsim: http://gpcr-modsim.org/
- Cloudgene: http://www.cloudgene.io/
- Seven Bridges: https://www.sevenbridges.com/platform/
- Nextflow Tower: https://cloud.tower.nf/

## Workflow engines for Bioinformatics

- Snakemake: https://snakemake.readthedocs.io/en/stable/
- Nextflow: https://www.nextflow.io/
- bPipe: http://docs.bpipe.org/Overview/Introduction/
- Moa: https://moa.readthedocs.io/en/latest/index.html
- bcBio-NextGen: https://github.com/bcbio/bcbio-nextgen
- Piper: https://github.com/johandahlberg/piper
- Biojulia: https://biojulia.net/
- SeqPig: https://github.com/HadoopGenomics/SeqPig
- GenPipes: https://genpipes.readthedocs.io/en/latest/about/index.html
- BioWDL: https://biowdl.github.io/

## Repository

- Snakemake catalog: https://snakemake.github.io/snakemake-workflow-catalog/
- nf-core: https://nf-co.re/pipelines
- snakePipes: https://snakepipes.readthedocs.io/en/latest/

## Tutorials

- Introduction to Nextflow: https://sateeshperi.github.io/nextflow_varcal/nextflow/
- Introduction to snakemake: https://hackmd.io/7k6JKE07Q4aCgyNmKQJ8Iw?view
- Comparision of Bioinformatics workflows: https://github.com/GoekeLab/bioinformatics-workflows

## Why using a workflow manager?

- input data description
- parameters for each individual tool
- tool versioning tracking
- generate execution reports with detailed information
- Provide the execution environment (conda environment, singularities, dockers)
- the software version of the workflow manager (which can also be provided in a container)
- resource usage information (amount of memory, execution time, number of CPUs)
- Automatic visualization of the pipeline steps
- the workflow itself can be publicly archived and made citable by obtaining a version-specific digital object identifier (DOI) through Zenodo
- Scalability: Adapt processing to the size of the data and the resources available
- Re-entrancy: "Workflow managers can handle such events by enabling re-entrancy. Re-entrancy allows users to run a pipeline from its last successfully executed step, rather than from the beginning, in the case of a disruption."

        
