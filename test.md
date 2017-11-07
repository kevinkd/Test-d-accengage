.Implémenter ces fonctions

fonction order ( $array , $ascOrDesc = 'asc' ) { 
  $i =0,$tmp=0;
  for(i=0; i<count(array); i++)
   for(j=i+1; j<count(array); j++) {
      if(array(i)>array(j)) {
         tmp = array(i);
         array(i) = array(j);
         array(j) = tmp;     
      }
   }
 var_dump (order ($array, 'asc'));
 return $array ; 
 } 
 fonction oddOrEven ($array, $oddOrEven = 'even') { 
  for(i=0; i<count(array); i++)
   if(array(i) % 2 == 0) {
        var_dump (oddOrEven ($array, 'pair'));    
        return $array ; 
      }
    else
         var_dump (oddOrEven ($array, 'impair')); 
         return $array ; 
   }
 } 
 

.Corrigez ces phrases SQL, cela devrait retourner le nombre de livres par Auteur
SELECT  a.authorId , a.nom , count( b.bookId ) AS nblivres,
FROM livres b
INNER JOIN auteur ON b.bookId = auteur.authorId
GROUP BY a.nom 
 
 
.Quel est le problème avec ce code JS:

var tableau = [ 1 , 2 , 3 ];
var  total  =  0 ;
tableau.forEach (( nombre ) => {
  total + = nombre;
});
console.log(total);


.Ecrire un regexp qui permet de capturer toute la ligne en terminant par un .ou un-
 
#.[\.\-]$#
