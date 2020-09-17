# plinkR

Just here for easy compiling of the pgenlibr package here: https://github.com/chrchang/plink-ng/tree/master/2.0/pgenlibr  
  
pgen <- NewPgen("myPgenFile.pgen")  
buf <- Buf(pgen)  
Read(pgen, buf, 1) (Read the first variant; 1-based indexing)  

Read(pgen, buf, 10) (Read the 10th variant)  
