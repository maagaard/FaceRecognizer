# Advanced Machine Learning 02460 - Project
## Project meeting - Week 5
**07-04-2016**


## Overview


# Progress since last time
-  

# Today
- Better value for margin
    * We now compute it
- Code profiling
    - The intersect(A,B) used for finding correct targets and impostors, is very slow. Instead of intersect, the underlying method used by intersect(A,B), ismember(A,B) can be used. The ismember(A,B) returns an array indicating which values of A that is also found in B. 

# Work for next week. 
- Test classification
- Visualize behavior of gradient
- Make some more examples for visualization 

# Discussions
- Loss function numerisk gradient vist korrekt

- Margen/Skalering diskussion
   - 1 margen ved lav scalering af data tager alt med kæmpe push bidrag 
   - 1 margen ved stor scalering af data kæmpe pull bidrag
   - Max(Max(target)) giver for stor margen ved outliers
   - Median(Meadian(target))
   - loss function bliver flad ved for lav scalering
   - Scaler efter cov(data) for at normaliser scalering
   
- Active sets
   - Hvis de har imposters er de aktive, ellers ikke
   - 

- Rigtig dataset

- Hvad med andre normer - evt. 1 norm




# All groups meeting
- lfw_sifts.mat contains the treated face data
