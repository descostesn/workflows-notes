# workflows-notes

## Publications

  * [Experiences with workflows for automating data-intensive bioinformatics](https://biologydirect.biomedcentral.com/articles/10.1186/s13062-015-0071-8)
  * [A review of bioinformatic pipeline frameworks](https://academic.oup.com/bib/article/18/3/530/2562749)
  * [The nf-core framework for community-curated bioinformatics pipelines](https://www.nature.com/articles/s41587-020-0439-x)
  * [DolphinNext: a distributed data processing platform for high throughput genomics](https://bmcgenomics.biomedcentral.com/articles/10.1186/s12864-020-6714-x)
  * [Reproducible, scalable, and shareable analysis pipelines with bioinformatics workflow managers](https://www.nature.com/articles/s41592-021-01254-9)

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
- Toil: https://github.com/DataBiosphere/toil

## Repositories

### Workflows collection

- Snakemake catalog: https://snakemake.github.io/snakemake-workflow-catalog/
- nf-core: https://nf-co.re/pipelines
- snakePipes: https://snakepipes.readthedocs.io/en/latest/
- GATK repository: https://github.com/search?q=GATK+pipeline&type=Repositories
- Galaxy: https://usegalaxy.org/workflows/list_published and https://usegalaxy.eu/workflows/list_published
- WARP (wdl): https://broadinstitute.github.io/warp/docs/get-started
- Intergalactic commission (peer-reviewed galaxy workflows): https://github.com/galaxyproject/iwc/
 
### Others

- List of engines not limited to Bioinformatics: https://github.com/pditommaso/awesome-pipeline
- Comparision of Bioinformatics workflows: https://github.com/GoekeLab/bioinformatics-workflows

## Tutorials

- Introduction to Nextflow: https://sateeshperi.github.io/nextflow_varcal/nextflow/
- Introduction to snakemake: https://hackmd.io/7k6JKE07Q4aCgyNmKQJ8Iw?view
- Comparision of Bioinformatics workflows: https://github.com/GoekeLab/bioinformatics-workflows
- Tips on using nf-core pipelines: https://u-bds.github.io/training_guides/nf_core_tips.html

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
- incremental build

## Non-DSL engines

"While graphical and DSL workflow managers are currently the most widely used frameworks for bioinformatics pipelines, there are some other types of workflow managers, such as programming-library-based tools. Programming-library-based workflow managers implement their pipeline management systems as a programming library for an existing, popular programming language." ([ref](https://www.nature.com/articles/s41592-021-01254-9))

- sciPipe: https://scipipe.org/ (programming-library-based tools)
- Luigi: https://github.com/spotify/luigi (programming-library-based tools)

"Workflow specifications provide a set of formalized rules for defining computational pipelines. This allows the separation of the pipeline definition from the execution environment, thereby adding another layer of abstraction. Workflow specifications enable the definition of pipelines that can be executed across workflow managers or execution environments that support the standard" ([ref](https://www.nature.com/articles/s41592-021-01254-9))
- CWL: https://www.commonwl.org/ (workflow specifications)
- cwltool: https://github.com/common-workflow-language/cwltool (CWL executor)
- CWL export by snakemake: https://snakemake.readthedocs.io/en/stable/executing/interoperability.html
- WDL: https://openwdl.org/ (workflow specifications)
- cromwell: https://github.com/broadinstitute/cromwell (WDL executor)
        
## Companies proposing workflow services

- DNA Nexus (CWL - focus on medicine and drug discovery): www.dnanexus.com
- Illumina (CWL - Nextflow)/ Illumina Connected Analytics (DRAGEN pipelines): https://www.illumina.com/products/by-type/informatics-products/connected-analytics.html
- Illumina basespace: https://www.illumina.com/products/by-type/informatics-products/basespace-sequence-hub/apps.html
- SevenBridges (CWL): https://www.sevenbridges.com/platform/

- 
