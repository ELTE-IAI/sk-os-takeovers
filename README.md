## open source under adversarial action by probabl and affiliates

This repository documents background material about three cases of
collaborative, community driven open source projects subjected
to adversarial or competitive action by
actors with ties to scikit-learn and probabl, within the last year:

* `lifelines` - new **copycat project** "`hazardous`", a "flagship" project of probabl
  funded and promoted for survival/hazard prediction, despite its incomplete,
  non-functional state; heavily wraps lifelines without proper credit
* `pyportfolioopt` - new **copycat project** "`skfolio`",
  promoted by scikit-learn social media accounts. One key maintainer of pyportfolioopt
  points prospective contributors to skfolio instead of the original.
* `skopt` / `scikit-optimize` - one maintainer, a core dev of scikit-learn, **shut down the project
  without informing other maintainers**, despite credible commitments
  to maintenance; kept ghosting their attempts at contact.

While probabl is not directly involved in all of the above, there are close links
through social media promotion, or core developer membership.

Actions are all in violation of
publicly stated [probabl values](https://github.com/ELTE-IAI/sk-os-takeovers/blob/main/re-probabl/probabl_values.jpg)
(statement does not imply intended attribution):

* individual stakeholder gain rather than supporting the ecosystem
* fragmentation rather than interoperability
* competition rather than collaboration
* stealth rather than accessibility


### lifelines - copycat "hazardous"

* lifelines - ecosystem cornerstone for survival modelling (together with scikit-survival)
* hazardous is one of probabl's official flagship projects. [screenshot from probabl webpage listing the project as core, retrieved 2024-06-09](https://github.com/ELTE-IAI/sk-os-takeovers/blob/main/re-lifelines/probabl-webpage-hazardous-screenshot-2024-06-09.png)
* [main branch (retrieved 2024-06-19)](https://github.com/ELTE-IAI/sk-os-takeovers/blob/main/re-lifelines/hazardous-main-2024-06-18.zip) and [most up to date branch "ICML 2024"](https://github.com/ELTE-IAI/sk-os-takeovers/blob/main/re-lifelines/hazardous-icml-2024-2024-06-18.zip) contain a highly incomplete package, heavily wrapping lifelines. Copycat.
* maintainers of lifelines were not aware about hazardous and were not contacted by probabl,
  see discussion with lifelines [part 1](https://github.com/ELTE-IAI/sk-os-takeovers/blob/main/re-lifelines/hazardous-lifelines-discuss1-2024-06-09.jpg) and [part 2](https://github.com/ELTE-IAI/sk-os-takeovers/blob/main/re-lifelines/hazardous-lifelines-discuss1-2024-06-09.jpg)

probabl involvement or relation:

* directly involved with copycat, hazardous is official project

vs values:

* stealth - lifelines (main equivalent package) was not informed and unaware. Development went on for 1 year in stealth.
* competition - copycat package that is heavily promoted, funded; no collaboration with lifelines or clear credit to
* individual stakeholder gain - used to promote probabl and profile of Olivier Grisel
* fragmentation - package landscape fragmented with equivalent functionality


### pyportfolioopt - copycat "skfolio"

* cornerstone package for portfolio modelling, [master branch retrieved 2024-06-18](https://github.com/ELTE-IAI/sk-os-takeovers/blob/main/re-pyportfolioopt/PyPortfolioOpt-master.zip)
* skfolio functional copycat of pre-existing pyportfolio package, started Dec 2023 [main branch retrieved 2024-06-18](https://github.com/ELTE-IAI/sk-os-takeovers/blob/main/re-pyportfolioopt/skfolio-main.zip)
* promoted by official scikit-learn account on linkedin: [linkedin post URL](https://www.linkedin.com/posts/scikit-learn_github-skfolioskfolio-python-library-activity-7152698232442093570-01Bk?utm_source=share&utm_medium=member_desktop), [screenshot](https://github.com/ELTE-IAI/sk-os-takeovers/blob/main/re-pyportfolioopt/skfolio-linkedinpost-2024-Feb.jpg)
* pyportfolio started to broadcast "requesting maintenance" messages in 2022.
  [message "looking for maintainers" on readme from 2022-11-26 to 2023-04-21](https://github.com/ELTE-IAI/sk-os-takeovers/blob/main/re-pyportfolioopt/pyportfolioopt-maintainer-search-2023.jpg)
* when writing to single email given in readme ([screenshot of pointer until 2024-03](https://github.com/ELTE-IAI/sk-os-takeovers/blob/main/re-pyportfolioopt/pyportfolioopt-single-email-2024-03-12)), [maintainer points to skfolio](https://github.com/ELTE-IAI/sk-os-takeovers/blob/main/re-pyportfolioopt/skfolio-email1-2024-01-24.jpg)
* [maintainer then ghosts and does not onboard](https://github.com/ELTE-IAI/sk-os-takeovers/blob/main/re-pyportfolioopt/skfolio-email2-2024-01-24.jpg)

probabl involvement or relation:

* owned by a French corporate developer, connected with affilates of sklearn, probabl, numfocus
* promoted heavily by official scikit-learn account. This is very rare for "unaffiliated" pcakages.

vs values:

* competition, fragmentation - no effort to integrate or collaborate with pyportfolioopt
* stealth - skfolio package released from stealth and promoted shortly after


### scikit-optimize - shut down by sklearn developer, locking out other maintainers

* cornerstone package for ML/AI algorithm tuning
* repo was archived on Feb 28, 2024, to the surprise of some maintainers.
  This effectively sends out a message that the project is defunct.
  [screenshot of archiving message](https://github.com/ELTE-IAI/sk-os-takeovers/blob/main/re-skopt/skopt-archived-2024-02-28.jpg)
* done by betatim (Tim Head) without communicating with other maintainers,
  despite credible commitment to continued maintenance. See discussion
  with locked out maintainer [part 1](https://github.com/ELTE-IAI/sk-os-takeovers/blob/main/re-skopt/skopt-discussion1-2024-06-03.jpg) [part 2](https://github.com/ELTE-IAI/sk-os-takeovers/blob/main/re-skopt/skopt-discussion2-2024-06-04.jpb) [part 3](https://github.com/ELTE-IAI/sk-os-takeovers/blob/main/re-skopt/skopt-discussion3-2024-06-04.jpg) [part 4](https://github.com/ELTE-IAI/sk-os-takeovers/blob/main/re-skopt/skopt-discussion3-2024-06-10.jpg)
* betatim ignores attempts of other maintainer to get in touch (see above)

probabl involvement or relation:

* betatim - the person who shut down the project - is a scikit-learn core developer,
  and hence closely integrated with probabl.

vs values:

* stealth: done unilaterally without informing other developers, locking out the community.
* fragmentation, competition: shutdown of popular package has led to multiple uncoordinated attempts to fork and to continue maintenance. Fragments and weakens open ecosytstem for AI algorithm tuning significantly.
