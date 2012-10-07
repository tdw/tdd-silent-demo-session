# TDD silent demo session

This silent demo serves as a __introduction__ to the TDD mindset, flow and practice. 
It has been tested live on real audience and has proven to work quite well to get people
interested and join the debate.

It consists of 3 distincts phases.

*    Phase 1 - Mail from business
*    Phase 2 - Bug fix using TDD
*    Phase 3 - Listing PROS & CONS

## Phase 1 - Mail from business

Explain to your audience that you are going to replay in front of them a scenario that 
has happen to you in real life during you daily job as a TDD developer 
(and in my case this is true and makes it more interesting, but I am sure you can find
the same kind of situation for you)

Simulate that you just received an email from business and show it to them:

> __From__: bob@mycompany.com

> __Subject__: [URGENT] IL faut patcher la PROD maintenant

> Salut Simon,

> Dans la dernière version, lorsque l'utilisateur veut afficher son adresse, 
il y a des espaces blancs qui s'insèrent et l'affichage est donc incorrect.  

> Voici un exemple:

>     6       avenue            leclerc

>     75003      PARIS

>                FRANCE

> alors que l'on veut

>     6 avenue leclerc

>     75003 PARIS

>     FRANCE

> Michel du back office m'a dit que c'est un formatting qui se fait 
lors de la sauvegarde des adresses. Des espaces blancs sont insérés 
pour pouvoir rester compatible avec l'affichage d'autres applications.

> Pour notre web app, il va falloir enlever les espaces blancs avant l'affichage. 
En gros, les uses cases seraient les suivants:

>     '6 avenue leclerc' --> '6 avenue leclerc'

>     '6    avenue      leclerc' --> '6 avenue leclerc'

>     '   6   avenue      leclerc   ' --> '6 avenue leclerc'

> Peux tu faire un patch pour la production dès que possible ?

> Merci,

> Bob

## Phase 2 - Bug fix using TDD

Now you explain that you are going to do the patch. You can add that it is nice that in the e-mail
they also psecify some uses cases and it is going to help you start.

Now you are on to your best TDD hard core session ever. But before tell the audience that
it is going to be a a "silent" session meaning

* The audience can not ask any questions or participate. 
They just watch closely what you are doing. __Encourage them to take notes__.

* During your TDD flow and implementation, you will __think out loud__. 
It means the audience will hear all your reflexions and therefore 
will be able to follow closely the TDD mindset and flow

## Phase 3 - Listing PROS & CONS

This is the most interesting part of the session. 

Explain to your audience that you are all going to fill in a table with 2 columns. 
So open a text editor and project it for everyone to see.

This table contains one PROS column and one CONS column.

So now ask your audience to list PROS & CONS they see in using TDD with their own words. 
Each time try to sum each person idea into the right column. Do that until you all run out of ideas.

For timid audience you should lead them to PROS & CONS.

## Conclusion

The result is that:

*    **a majority of persons from the audience (most often all of them actually)
has recognized and acknowlegded the advantages of using TDD without you influencing them.**

*    **you have also listed the disadvantages of TDD therefore recognizing that there are some.
But it will give you the opportunity in later workshops to address them one by one.**








