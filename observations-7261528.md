# Lab 4 Observations
developer：Jon Connor
1. After exchanging the two inside for-loop, some of the unprotected values which were not 10000 before change to 10000.
2. After incrementing both values in the same for-loop,  the unprotected values which were  10000 before change to other number.
3. After counting only to 10 inside each task, we can find that all values change to 100.
I expect the counting number not to change in these tests, because it leads to a big mess.
With this observation, I can know the benefits of protected object and try to change it to protected version.