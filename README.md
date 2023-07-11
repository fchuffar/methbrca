# momic

An R package allowing to visualize multi omic data at the gene level.

  
**Install**
  
```
devtools::install_github("fchuffar/momic")
```
  
  
**Developement**

On a terminal:

```
git clone git@github.com:fchuffar/momic.git
cd momic
```

Under R:
    
```
devtools::document(); 
devtools::install(); 
Sys.setenv('_R_CHECK_SYSTEM_CLOCK_' = 0)
devtools::check()
devtools::build()
```

**Vignettes**


Under R, in the vignette directory:
    
```
rmarkdown::render("01_momic_meth_vs_trscr.Rmd")
```
