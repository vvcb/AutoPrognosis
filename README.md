# AutoPrognosis: Automated Clinical Prognostic Modeling via Bayesian Optimization with Structured Kernel Learning 

<<<<<<< HEAD
[AutoPrognosis](https://icml.cc/Conferences/2018/Schedule?showEvent=2050): A system for
=======
[AutoPrognosis](https://icml.cc/Conferences/2018/Schedule?showEvent=2050): a system for
>>>>>>> 0c1919b7141275e3f7e84f07c13ed63dec85c739
automating the design of predictive modeling pipelines tailored for
clinical prognosis.

See <project_dir>/doc/install.md for installation instructions

## [Video Presentation Autoprognosis](https://www.youtube.com/watch?v=d1uEATa0qIo)

You can find a presentation by Prof. van der Schaar describing AutoPrognosis here:
https://www.youtube.com/watch?v=d1uEATa0qIo

## [Slides Autoprognosis](doc/AP_summary.pdf)

## Usage

```
python3 autoprognosis.py -i <data.csv> --target <response variable> -o <outdir>  [ -n <num_sample> --it <num_iterations> ]
```

The results can be found in two json files: <outdir>/result.json and <outdir>report.json. They can be shown with:

```
python3 autoprognosis_report.py -i <outdir>
```
See also jupyter notebooks tutorial_autoprognosis_*.ipynb

## Know issues

- Acquisition function LCB generates excesive warnings "The set cost
  function is ignored! LCB acquisition does not make sense with
  cost.". This can be ignored.

## References
1. [AutoPrognosis: Automated Clinical Prognostic Modeling via Bayesian Optimization with Structured Kernel Learning](https://arxiv.org/abs/1802.07207)
2. [Prognostication and Risk Factors for Cystic Fibrosis via Automated Machine Learning](https://www.nature.com/articles/s41598-018-29523-2)
3. [Cardiovascular Disease Risk Prediction using Automated Machine Learning: A Prospective Study of 423,604 UK Biobank Participants](https://www.ncbi.nlm.nih.gov/pubmed/31091238)
