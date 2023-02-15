#KAKO klonirati repozitorij i napraviti virtualno okruzenje i instalirati sve pratece requirements#

**git clone url** (url - https://github.com/aheacon/school_enrollment.git) **Kloniranje repositorija na osnovu URLa.**
**cd repository** (u ovom slucaju cd school_enrollment, pristupanje unutar direktorija/foldera. cd je jedna od uobicajenih bash komandi unutar Linuxa, kada se zeli izaci iz svih foldera - ukucati cd ..)
**pip install virtualenv** (ukoliko prethodno nije instaliran VENV - potrebno je iskoristiti ovu komandu, pip je akronim za python package manager, a VENV je nacin izoliranja projekata i zadavanja samo potrebnih pipova koji su potrebni za projekat)
**mkdir env** (nakon toga, potrebno je kreirati direktorij/folder, u ovom slucaju naziva env - jos jedna bash komanda mkdir)
**virtualenv school_enrollment** (definisanje venv za navedeni repozitorij)
**source school_enrollment/bin/activate**
Ukoliko je ispred naziva korisnika nalazi naziv repositorija u zagradi, to je znak da smo pristupili venv.
**pip install -r requirements.txt** (ovo predstavlja instaliranje svih pipova koji se nalaze u odgovarajucem txt fajlu requirements)

Svaki put kada se pristupa venvu school_enrollment potrebno je ukucati virtualenv school_enrollment u terminalu. 

