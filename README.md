# GARI
This work introduces a simple project called GARI (Genetic Algorithm for Reproducing Images).
GARI reproduces a single image using Genetic Algorithm (GA) by evolving pixel values.

This project works with both color and gray images without any modifications.
Just give the image path.
Using three parameters, we can customize it to statisfy our need. 
The parameters are:
    1) Population size. I.e. number of individuals pepr population.
    2) Mating pool size. I.e. Number of selected parents in the mating pool.
    3) Mutation percentage. I.e. number of genes to change their values.

Value encoding used for representing the input.
Crossover is applied by exchanging half of genes from two parents.
Mutation is applied by randomly changing the values of randomly selected 
predefined percent of genes from the parents chromosome.

This project is implemented using Python 3.5 by Ahmed F. Gad.
Contact info:
ahmed.fawzy@ci.menofia.edu.eg
https://www.linkedin.com/in/ahmedfgad/

Here is an example of input image and how it is evolved after some iterations.

Original Image
![fruit](https://user-images.githubusercontent.com/16560492/36948808-f0ac882e-1fe8-11e8-8d07-1307e3477fd0.jpg)

Generation 0
![solution_0](https://user-images.githubusercontent.com/16560492/36948589-b47276f0-1fe5-11e8-8efe-0cd1a225ea3a.png)

Generation 1000
![solution_1000](https://user-images.githubusercontent.com/16560492/36948823-16f490ee-1fe9-11e8-97db-3e8905ad5440.png)

Generation 2500
![solution_2500](https://user-images.githubusercontent.com/16560492/36948832-3f314b60-1fe9-11e8-8f4a-4d9a53b99f3d.png)

Generation 4500
![solution_4500](https://user-images.githubusercontent.com/16560492/36948837-53d1849a-1fe9-11e8-9b36-e9e9291e347b.png)

Generation 7000
![solution_7000](https://user-images.githubusercontent.com/16560492/36948852-66f1b176-1fe9-11e8-9f9b-460804e94004.png)

Generation 8500
![solution_8500](https://user-images.githubusercontent.com/16560492/36948865-7fbb5158-1fe9-11e8-8c04-8ac3c1f7b1b1.png)

Generation 15000
![solution_15000](https://user-images.githubusercontent.com/16560492/36948877-96df3534-1fe9-11e8-8722-697d1047c1ff.png)


