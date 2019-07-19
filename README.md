
# More Mixed Models

In the R world, `lme4` is a great package for mixed model estimation,
and the most widely used for such models. For standard settings, few
tools will do the trick as easily or as quickly, and because of that,
its approach has been emulated in other packages and statistical
programs. However, that ease and efficiency comes at a price of being
able to do more complex models, so at some point you may need to switch
gears. This workshop will demonstrate other ways to potentially get what
you need.

Demonstration will (potentially) include the following, along with some
discussion of strengths and/or drawbacks to use.

  - `glmmTMB`: heterogeneous variances, auto-correlated residuals,
    zero-inflated models
  - `rstanarm`, `brms`: Bayesian approaches
  - `mgcv`: additive effects, robust models, big data
  - `statsmodels`: in case you’re in the Python world.

This workshop assumes basic familiarity with mixed models, and
familiarity with R, especially the `lme4` package. However, this is a
brief demonstration with a simple goal of bringing about awareness of
other useful tools, so one can simply attend to hear about them.

[Click to download this
repo](https://github.com/m-clark/more-mixed-models-2019/archive/master.zip).
For the workshop, you can run the code in `mmm_notebook.Rmd` as we go
along. If you just want to follow along/see the content, open `mmm.html`
in your browser after downloading the repo.
