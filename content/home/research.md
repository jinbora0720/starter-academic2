+++
# Experience widget.
widget = "experience"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 20  # Order that this section will appear.

title = "Research"
subtitle = ""

# Date format for experience
#   Refer to https://sourcethemes.com/academic/docs/customization/#date-format
date_format = "Jan 2006"

# Experiences.
#   Add/remove as many `[[experience]]` blocks below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin/end multi-line descriptions with 3 quotes `"""`.

[[experience]]
  title = "Joint Species Distribution Modeling with Ecological Networks"
  company = "with Jennifer Kampe, David Dunson, and Otso Ovaskainen"
  company_url = ""
  date_start = "2022-09-01"
  date_end = ""

description = """

* Incorporate interactions among species to increase interpretability of a joint species distribution model.
* Separate dependence in co-occurrences of multiple species into two parts: one part attributable to shared latent factors such as habitat conditions and the other attributable to between-group interactions encoded in an undirected graph.

"""

[[experience]]
  title = "Effects of PFAS on North Carolina Thyroid Cancer Clusters"
  company = "with James Matuk, Amy H. Herring, and Kate Hoffman"
  company_url = ""
  date_start = "2022-09-01"
  date_end = ""

description = """

* Identify thyroid cancer clusters in North Carolina.
* Reveal spatial, causal, and socioeconomic relationships between the cancer clusters and PFAS.

"""

[[experience]]
  title = "Spatial Predictions on Physically Constrained Domains: Applications to Arctic sea salinity data"
  company = "with Amy H. Herring and David Dunson"
  company_url = ""
  date_start = "2020-09-01"
  date_end = ""

description = """

* https://doi.org/10.48550/arXiv.2210.03913

* R package [boraGP](https://github.com/jinbora0720/boraGP)

* Motivated by applications in point-referenced geostatistics that have measurements collected and meaningful only within a constrained domain.

* Develop the Barrier Overlap-Removal Acyclic directed graph GP (BORA-GP), a scalable GP method that incorporates the constrained domain via sparsity-inducing DAGs.  

* Enable characterization of dependence in constrained domains by removing an edge in a DAG if a linear path between two points overlaps physical barriers.

* Analyze sea surface salinity in the Arctic Ocean.

"""

[[experience]]
  title = "Bag of DAGs: Flexible Nonstationary Modeling of Spatiotemporal Dependence"
  company = "with Michele Peruzzi and David Dunson"
  company_url = ""
  date_start = "2020-09-01"
  date_end = ""
  description = """

* https://doi.org/10.48550/arXiv.2112.11870

* R package [bags](https://github.com/jinbora0720/bags)

* [Simple example demonstration](/media/BAGs/example.html)

* Propose a computationally efficient approach to construct a class of nonstationary spatiotemporal processes using multiple yet simple directed acyclic graphs (DAGs), which leads to computational efficiency, flexibility, and interpretability in point-referenced geostatistical models.

* Develop Bag of DAGs processes (BAGs) whose nonstationarity is induced via local mixtures of DAGs. Directed edges in DAGs are alternative and competing assumptions on directional correlation patterns in space and time.

* Analyze spatiotemporal variability of fine particulate matter (PM2.5) in South Korea and California, US, in which a directed edge represents a prevailing wind direction causing some associated covariance in the pollutants.

"""

[[experience]]
  title = "Bayesian Matrix Completion for Hypothesis Testing"

company = "with David Dunson, Julia E. Rager, David Reif, Stephanie M. Engel, Amy H. Herring"
  date_start = "2019-07-01"
  date_end = "2022-10-01"

description = """

* https://doi.org/10.48550/arXiv.2009.08405
* To appear in *Journal of the Royal Statistical Science: Series C*.
* Adapt Bayesian heteroscedastic nonparametric regression to a multiple hypothesis testing framework.  
* Impose a generalized latent factor model to form a non-exchangeable prior for testing.
* Develop a matrix completion method for a latent matrix.
* Tackle sparsity of the ToxCast data using hierarchical framework.
* Enable prediction for non-tested chemical’s activity.
* Broaden the definition of activity including heteroscedasticity.

"""

+++
