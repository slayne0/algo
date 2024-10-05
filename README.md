function addition(a, b) {
  return a + b } 

console.log(addition(2, 3)); // Résultat attendu : 5




function salutation(nom) {
  return ("bonjour " + nom) } 

console.log(salutation("Alice")); // Résultat attendu : "Bonjour Alice"





function estPair(nombre) {
  if (nombre % 2 === 0) { return ("true") }
  else { return ("false") } }

console.log(estPair(4)); // Résultat attendu : true console.log(estPair(7)); // Résultat attendu : false







function aireRectangle(longueur, largeur) {
  return longueur * largeur } 
console.log(aireRectangle(5, 3)); // Résultat attendu : 15






function estMajuscule(chaine) {
  if (toUpperCase(chaine) === chaine) { return ("true") }
  else { return ("false") } } 


//console.log(estMajuscule("HELLO")); // Résultat attendu : true estMajuscule("Hello"); // Résultat attendu : false






function maxDeuxNombres(a, b) {
  if (a > b) {return ("a")}
  else {return ("b")}
}

console.log(maxDeuxNombres(5, 10)); // Résultat attendu : 10






function difference(a, b) {
  result = (a - b)
  
  return result
}

console.log(difference(10, 3)); // Résultat attendu : 7






function convertirEnCelsius(fahrenheit) {
  result = (fahrenheit - 32) * 5/9


  return result
}
console.log(convertirEnCelsius(100)); // Résultat attendu : 37.7778







function estMajeur(age) {
  if (age > 17) {return ("true")}
  else {return ("false")}
}


console.log(estMajeur(20)); // Résultat attendu : true
console.log(estMajeur(16)); // Résultat attendu : false





function maxTroisNombres(a, b, c) {
  result =Math.max(a, b, c)
  
  return result
  
}
console.log(maxTroisNombres(3, 7, 5)); // Résultat attendu : 7