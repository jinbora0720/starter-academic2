+++
# Experience widget.
widget = "experience"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 40  # Order that this section will appear.

title = "Current Research"
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
  title = "Effects of Short-term Air Pollution on COVID-19"
  company = "with David Dunson"
  company_url = ""
  date_start = "2020-09-01"
  date_end = ""
  description = """ 

* Build a Bayesian model to predict effects of PM2.5 with and without wildfires.

* Include information about dynamics of wildfires and their progression into a Gaussian process (GP) using multiple directed acyclic graphs (DAG). 

* Investigate the short-term effect of PM2.5 on respiratory diseases including COVID-19.

"""

[[experience]]
  title = "Prediction for Per- and polyfluoroalkyl Substances in relation to Stream Networks"
  company = "with Amy H. Herring"
  company_url = ""
  date_start = "2020-09-01"
  date_end = ""

description = """

* Develop a predictive spatial model for per- and polyfluoroalkyl substances (PFAS) in public water system (PWS) along with uncertainty quantification. 

* Identify upstream and downstream information of PWSs in relation to the nearest stream network and construct a corresponding DAG.

* Fit a multivariate GP using the DAG, incorporating external factors such as known sources or known relationship between PFAS compounds.        

"""

[[experience]]
  title = "Bayesian Matrix Completion for Hypothesis Testing"

company = "with David Dunson, Julia E. Rager, David Reif, Stephanie M. Engel, Amy H. Herring"
  date_start = "2019-07-01"
  date_end = ""

description = """

* *submitted*  https://arxiv.org/pdf/2009.08405.pdf

* Adapted Bayesian heteroscedastic nonparametric regression to a multiple hypothesis testing framework.  
* Imposed a generalized latent factor model to form a non-exchangeable prior for testing. 
* Developed a matrix completion method for a latent matrix. 
* Tackled sparsity of the ToxCast data using hierarchical framework. 
* Enabled prediction for non-tested chemical’s activity. 
* Broadened the definition of activity including heteroscedasticity. 

"""

+++