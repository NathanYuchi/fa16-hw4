## Questions

1. What is the difference between new and create for a model?
New instantiates a model but doesn't put it into the data base instantly.
Properties of the newly created model must be set independently.
Model is put into the database with the save command.

Create instantiates a model with its properties filled in and puts it into the
database in one line.

2. What command combined with new will emulate the same behavior as create?
save
3. What is the default integer column that exists on every table but we did NOT define?
id
4. What single line of ruby code can insert a cat with the name "Kira" in the database?
Cat.create(:name=>'Kira')
5. How did you like this homework in comparison with the previous homeworks?
This one was a bit more frustrating because of some errors, but in the end
makes sense.  The topic also seems very useful.
