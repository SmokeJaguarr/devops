# DevOps iescējiem 2# mājasdarbs
# Uzdevumi

1) Salīdzināt vienādu failu (ne README) hash no mapes module_1 un
      module_2. Vai git redz atšķirību starp šiem failiem?

2) Pārbaudīt kādas izmaiņas tika veiktas iepriekšējās nedēļas laikā. Atrast
   vismaz divus veidus kā to izdarīt
   Izmaiņas varam aplūkot caur github https://github.com/hashicorp/terraform/commits/main
   https://github.com/{lietotāja nosuakums}/{repositorija nosuakums}/commits/{brancha nosuakums}
   vai
   ```git log --since=1.weeks```, kas ir veids kā mēs varam apskatīt pēdējās nedēļas commitus
3) Atrast commit kurus veica autors - “Laura Pacilio”
   ```git log --author="Laura Pacilio"```
  
4) Atrast vai Laura ir veikusi commit pagājušā gada septembrī?
Laura ir veikusi 7 commit pagājušā gada septembrī 
   ```git log --author="Laura Pacilio" --since="Sep 1 2021" --until="Sep 30 2021"```
5) Vai Laura ir veikusi commit vakar?
Nē, pēdējais commit ir bijis 20. aprīlī.
   


## Autors
Dāvis