# stan_sandbox

Repo to be used as a binder background with Stan tools.
Follows the idea given in [arviz_sandbox](https://github.com/arviz-devs/arviz_sandbox) and [arviz-misc](https://github.com/arviz-devs/arviz_misc)


## Use
Serve with the environment in [stan_sandbox](https://github.com/ahartikainen/stan_sandbox)
for convenience and speed, see
[this post](https://discourse.jupyter.org/t/tip-speed-up-binder-launches-by-pulling-github-content-in-a-binder-link-with-nbgitpuller/922)
in Jupyter Discourse for a detailed description.

To generate the shield with the link to the binder environment:

* Generate the binder link to run the notebook in the sandbox environment.
  There is a helper page [nbgitpuller link generator](https://jupyterhub.github.io/nbgitpuller/link?tab=binder).
  The `Binder` tab allows to specify
  * `Git Environment Repository URL`: `https://github.com/ahartikainen/stan_sandbox`
  * `Git Content Repository URL`: e.g. `https://github.com/ahartikainen/BayesianWeather`
  * and the file or folder to be opened: e.g. `RainGauge`
* Create a custom shield from [Binder docs](https://mybinder.readthedocs.io/en/latest/howto/badges.html)
