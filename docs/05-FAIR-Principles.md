# FAIR Principles {#fair-principles}

## What is FAIR data?
<style>
div.blue { background-color:#e6f0ff; border-radius: 5px; padding: 10px;}
</style>
<div class = "blue">
FAIR data is **Findable**, **Accessible**, **Interoperable** and **Reusable**.
</div>
These principles are designed to help both humans and machines find and reuse data as easily as possible. They are aspirational but tangible steps can be made towards realising them.

You can read about the ethical values underlying the FAIR principles via the FAIR Cookbook [here](https://fairplus.github.io/the-fair-cookbook/content/recipes/introduction/FAIRplus-values.html).

### Findable {-}
**Findable** is all about making sure data/resources are as easy to find as possible.

How we're making resources **findable** at Cloud-SPAN:

- We have added rich metadata to our teaching resources using the [Bioschemas](https://bioschemas.org/) protocol for training materials.
- We have assigned DOIs to our training materials by depositing them in Zenodo.
- We will be registering our training materials with TeSS, a repository for life sciences training resources.
- We will be assigning persistent identifiers to our teaching materials to prevent "link rot", or broken links.

### Accessible {-}
**Accessible** means it is easy to find out how to access the data/resources.

How we're making resources **accessible** at Cloud-SPAN:

- Our training materials will be openly available, with no caveats, for use by those who cannot attend our workshops or who prefer self-led study.
- We state this in the metadata of resources and on the webpages hosting the courses.

### Interoperable {-}
**Interoperable** means data/resources can be easily integrated with other data/resources, and be viewable in different programs, applications or workflows.

How we're making resources **interoperable** at Cloud-SPAN:

- We provide data for analysis in de facto standard file formats, such as the FASTQ format for sequencing data.
- We write our training resources in Markdown, a widely used and platform-independent text formatting language which renders in all browsers.
- We use [Bioschemas](https://bioschemas.org/profiles/TrainingMaterial/0.9-DRAFT-2020_12_08) markup to add metadata to our resources, which is part of an initiative to standardise how search engines read webpages containing data.
- Within our metadata we use the [EDAM topic ontology](http://edamontology.org/page) to describe the topics our courses cover.

### Reusable {-}
**Reusable** is about making sure that data/resources are suitable for re-use in different settings by including "richly described metadata" and applying a suitable licence.

How we're making resources **reusable** at Cloud-SPAN:

- We have tagged our resources with metadata properties which conform to the Bioschemas suggested list of properties for biosciences training materials.
- We have applied Creative Commons Attribution 4.0 International (CC-BY) licences to our training materials - this is stated in the metadata, in the GitHub repository and on the webpages hosting the courses.
- We welcome (and encourage!) outside contributions of explanations and examples - see the [Ways to contribute] for more information.
