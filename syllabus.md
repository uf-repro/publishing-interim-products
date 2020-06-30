# Syllabus

## Intro

* Motivations
  - **Academic systems evaluate people**
    + I dislike this, but that doesn't make it less true
  - Success requires self-advocacy
    + NOT the same as boasting
    + make it **easy for other people to find and learn about your work**
* Learning Outcomes
  - understand the FAIR principles as they relate to scientific data management
  - explain the benefits of ORCID and Google Scholar profiles
  - define DOI, its attributes, and uses
  - identify tools and platforms for publishing interim research products
* Costs
  - to my knowledge, all of the tools introduced here are *free*
    + they may have paid tiers with additional features
    + funding sources often include large non-profits, funding agencies, etc.
  - **DO be aware that some platforms are run by for-profit publishing companies that are monetizing data on academics**

## FAIR

* What is it?
  - Guidelines for *Scientific Data*
    (but which apply more generally)
  - Findable
  - Accessible
  - Interoperable
  - Reusable
* Findable -- Can humans and machines find the data?
  - use metadata that accurately *describes* the content
  - use metadata that helps people *find* the content
* Metadata -- data that describes or gives information about other data
  - "The ISO country code for Namibia is NA, which has been a hilariously frustrating discovery I made while coding today [#rstats](https://twitter.com/hashtag/rstats)" - Sarah Bowden (@mamabphd) June 17, 2020 - https://twitter.com/mamabphd/status/1273352107240968193
  - the text of the tweet is content, and the hashtag identifies the content as related to R
  - metadata enables organization of tweets and findability of content (in this case without having to follow the original author or retweeters)
* Accessible -- there should be minimal barriers to access the data
  - e.g. no proprietary interfaces or software required
  - "available upon (reasonable) request" is insufficient!
  - use established methods to authenticate access to protected or private data
* Interoperable
  - use a common, shared format for storage
  - use a metadata standard for attributes
    + [FAIR Data Point](https://github.com/FAIRDataTeam/FAIRDataPoint/wiki/FAIR-Data-Point-Specification) is one
    + some are domain-specific, e.g. [Ecological Metadata Language](https://eml.ecoinformatics.org/)
* Reusable
  - add descriptions to help researchers identify whether it is suitable for their usage
  - use a legal license that enables re-use
    - e.g. CC-BY or CC-0
    - **don't use a code license**, e.g. MIT
  - include attribution and a description of how to cite the data
* Summary
  - FAIR principles are intended to make data more useful
    + the same principles apply for academic work!
* for more on data, see the [Research Data Management Libguide](https://guides.uflib.ufl.edu/datamanagement) 

## Personal Profiles

* Your Academic Identity
  - "Never ceases to amaze me how many postdoc scientists & other early career researchers have basically zero internet presence. Many have no website (beyond an impoverished uni site & even that's often missing), no readily available contact details, no pub list. Don't be invisible." - Chris Chambers (@chrisdc77) January 29, 2019 - https://twitter.com/chrisdc77/status/1090198315617132545
* is it FAIR?
  - Findable
  - Accessible
  - Interoperable
  - Reusable
* ORCID
  - https://orcid.org/
  - Open Researcher and Contributor IDentifier
  - unique ID that stays with you, regardless of changes in name, email, institution
  - common way to login to journals and identify yourself on publications
* Google Scholar
  - https://scholar.google.com/
  - IMO, does the best job of automatically identifying your *papers*
  - allows you to correct errors in the records for your works
  - citation statistics
    + these are imperfect, but LOTS of people care and this makes it easy for them to check
* LinkedIn
  - https://www.linkedin.com/
  - a *must* if you are considering a position in industry
  - use the right buzzwords for your skills
    + find people with jobs that you aspire to, and see what buzzwords they use
*  Other
  - ask around to see what sites are common in your field
    + not just what people use, but what they use to *look up or find applicants*
  - consider a personal website:
    + present more detailed information NOT found in other sites
    + many free and nice options (custom domains are about $10/year)

## DOI

* DOI = Digital Object Identifier
  - format
    + `10.NNNN/{suffix}`
    + `NNNN` identifies the registrant
    + `{suffix}` identifies the object
    + e.g. `10.5281/zenodo.3892184`
* DOI Properties
  - DOIs are permanent
    + the object and metadata record are archived
  - unambiguous
    + each DOI links to a unique object, and will only ever link to that object
* Why is this Important?
  - A given DOI always point to the same object.
    + (some exceptions for updating the metadata or deleting the object)
  - The scholarly record needs permanence.
    + someone else needs to be able to look up your sources
    + DOIs fit this role
  - Most journals issue a DOI for each article.
* Get DOIs for Your Work
  - If you have interim products, e.g.
    + code
    + datasets
    + protocols
    + images/video
  - **A DOI makes that work citable!**
    + for fellowship/grant/job applications

## Publishing Platforms

* Places that issue DOIs
  - preprint servers
  - data repositories
  - general-purpose repositories
  - tooling-specific repositories
* Preprints
  - papers, before peer-review and journal formatting
  - very common in math & physics, catching on elsewhere
  - why?
  - share your work more quickly
    + not delayed until peer review
  - (sometimes) get feedback
* Preprint servers
  - [arXiv.org](https://arxiv.org/) -- primary one for math and physics
    + uses their own indexing instead of DOI
  - [bioRxiv.org](https://www.biorxiv.org/) -- primary one for biology
  - [medRxiv.org](https://www.medrxiv.org/) -- primary one for health sciences
  - many others
    + including [OSF-hosted servers](https://osf.io/preprints/)
* Data Repositories
  - Zenodo
    + https://zenodo.org/
    + approved by UF IT for data storage (workshops forthcoming)
    + 50 GB capacity, supported by CERN
  - Dryad - https://datadryad.org
  - figshare - https://figshare.com
* Data Repositories  
  Additional Notes
  - Use whatever is common for your field / journal
  - Be aware of sharing restrictions for protected/private data
  - See the [Research Data Management Libguide](https://guides.uflib.ufl.edu/datamanagement) for details
* General Purpose Repositories
  - Open Science Framework
    + https://osf.io/
    + files can be uploaded or linked through github, dropbox, google drive, etc.
    + projects can be embedded within other projects
    + can issue DOIs for public projects
* Tooling-Specific  
  For specific (common) applications:
  - laboratory protocols and handy app -- https://www.protocols.io/
  - computer code -- https://github.com
    + does not issue DOI, but deposits to Zenodo
  - pre-register study design and analysis -- https://clinicaltrials.gov/, or https://osf.io/
  - [list of journals with registered reports](https://www.cos.io/our-services/registered-reports)

## Thanks
* Let me know what content you'd like to see
* Contact me for additional questions or consultation requests!
* Check back in on the libguide for more modules and contact info:
  - https://guides.uflib.ufl.edu/reproducibility
