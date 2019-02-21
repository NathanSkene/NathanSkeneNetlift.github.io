+++
# Display name
name = "Nathan Skene"

# Username (this should match the folder name)
authors = ["nathanskene"]

# Is this the primary user of the site?
superuser = false

# Role/position
role = ""

# Organizations/Affiliations
#   Separate multiple entries with a comma, using the form: `[ {name="Org1", url=""}, {name="Org2", url=""} ]`.
organizations = [ { name = "UK Dementia Research Institute", url = "https://ukdri.ac.uk/" },
  { name = "Imperial College", url = "https://www.imperial.ac.uk/dementia-research-institute/" }]

# Short bio (displayed in user profile at end of posts)
bio = "My research interests include human genetics, single cell -omics and neurobiology."

# Enter email to display Gravatar (if Gravatar enabled in Config)
email = ""

# List (academic) interests or hobbies
#interests = [
#    "Neurobiology",
#    "Human Genetics",
#    "Psychiatric Disorders",
#    "Transcriptomics",
#    "Bioinformatics"
#  ]

  

# Organizational groups that you belong to (for People widget)
#   Set this to `[]` or comment out if you are not using People widget.
#user_groups = ["Researchers", "Visitors"]
#user_groups = ["Principal Investigators"]
#user_groups = ["Principal Investigators"]
user_groups = ["Principal Investigators"]

# List qualifications (such as academic degrees)
[[education.courses]]
  course = "PhD in Molecular Biology"
  institution = "Wellcome Trust Sanger Institute, University of Cambridge"
  year = 2014

[[education.courses]]
  course = "MPhil in Computational Biology"
  institution = "University of Cambridge"
  year = 2009

[[education.courses]]
  course = "BSc in Artificial Intelligence and Cybernetics"
  institution = "University of Reading"
  year = 2008

# Social/Academic Networking
# For available icons, see: https://sourcethemes.com/academic/docs/widgets/#icons
#   For an email link, use "fas" icon pack, "envelope" icon, and a link in the
#   form "mailto:your-email@example.com" or "#contact" for contact widget.

[[social]]
  icon = "envelope"
  icon_pack = "fas"
  link = "n.skene@imperial.ac.uk"  # For a direct email link, use "mailto:test@example.org".

[[social]]
  icon = "twitter"
  icon_pack = "fab"
  link = "https://twitter.com/n_skene"

[[social]]
  icon = "google-scholar"
  icon_pack = "ai"
  link = "https://scholar.google.co.uk/citations?user=nu6vg78AAAAJ&hl=en&oi=ao"

[[social]]
  icon = "github"
  icon_pack = "fab"
  link = "https://github.com/NathanSkene"

# Link to a PDF of your resume/CV from the About widget.
# To enable, copy your resume/CV to `static/files/cv.pdf` and uncomment the lines below.
# [[social]]
#   icon = "cv"
#   icon_pack = "ai"
#   link = "files/cv.pdf"

+++

I am an independent <a href="https://www.edmondjsafra.org/">Safra</a> research fellow at Imperial College's Dementia Research Institute. My interests lie in using human genetics to gain insight into the neurobiology of brain disorders and cognitive traits. Currently I am focused on identifying the causal cell types underlying complex genetic traits. The motivation for this is that traditional approaches to science have been unable to yield definitive answers on which cell types are the primary cause of major diseases, such as Schizophrenia or Alzheimers. For instance, as the primary pathology in Alzheimers is neuronal/synapse loss, it was reasonably assumed for many years that the cause was neuronal, however analysis of genetic associatons shows that <a href="https://www.nature.com/articles/s41588-018-0311-9">most of the causal genes</a> are expressed in microglia.

I did my postdoctoral research at the Karolinska Institutet (KI) where I worked with <a href="http://www.hjerling-leffler-lab.org/">Jens Hjerling-Leffler</a> as part of the <a href="http://www.ucl.ac.uk/cortexlab/neuromics">Functional Neuromics</a> project. At KI we adapted single cell disassociation protocols such that we could obtain sufficient numbers of healthy interneurons from adult mice that we could catalogue the full complement of GABAergic cell types found in the <a href="journals.plos.org/plosbiology/article?id=10.1371/journal.pbio.2006387">CA1</a> region of the hippocampus. This work formed part of a broader effort to <a href="https://www.sciencedirect.com/science/article/pii/S009286741830789X">map all the cell types</a> in the mouse nervous system using single cell RNA-sequencing (the completed atlas can be viewed <a href="http://mousebrain.org/">here</a>). To enable greater insight into which of these cell types play a role in human disease/cognition we begun collaborating with <a href="https://ki.se/en/people/patrsu">Patrick Sullivan's</a> psychiatric genetics team: together we established the methods which enabled us to map the cell types underlying <a href="https://www.nature.com/articles/s41588-018-0129-5">Schizophrenia, Major Depression</a>, <a href="https://www.nature.com/articles/s41588-018-0152-6">IQ</a>, <a href="https://www.nature.com/articles/s41588-018-0151-7">Neuroticism</a>, <a href="https://www.biorxiv.org/content/early/2018/02/22/258533">Alzheimer's</a> and <a href="https://www.biorxiv.org/content/early/2018/02/01/214973">Insomnia</a>. We released the <a href="https://github.com/NathanSkene/MAGMA_Celltyping">MAGMA_Celltyping</a> package to enable others to apply this method to future GWAS studies. The KI single cell superset data which we used for cell type mapping is available <a href="www.hjerling-leffler-lab.org/data/scz_singlecell/">here</a>.

I gained an undergraduate degree in Artificial Intelligence and Cybernetics from the University of Reading in 2008, followed by an MPhil at the University of Cambridge in Computational Biology in 2009.  I went onto do a PhD in Molecular Biology at the Wellcome Trust Sanger Institute working with <a href="https://www.ed.ac.uk/clinical-brain-sciences/people/principal-investigators/professor-seth-grant">Prof Seth Grant</a>. During this time I worked on the <a href="http://www.genes2cognition.org/">Genes to Cognition programme</a>, analysing the transcriptomic changes seen in a mice carrying a wide range of synaptic mutations. 

Following my PhD I worked at the University of Edinburgh, where I studied how postnatal gene expression changes influence the <a href="https://elifesciences.org/articles/17915">onset</a> of psychiatric disorders. At this time I developed a method (<a href="https://github.com/NathanSkene/EWCE">Expression Weighted Celltype Enrichment</a>) which made it possible to show that <a href="https://www.frontiersin.org/articles/10.3389/fnins.2016.00016">microglia</a> are the celltype whose expression profile best explains the rare & common variant's associated with Alzheimer's disease.
