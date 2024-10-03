# algo


function addition(a, b) {
  return a + b
}
console.log(addition(2, 3)); // Résultat attendu : 5



function salutation(nom) {
  return ("bonjour " + nom)
}
console.log(salutation("Alice")); // Résultat attendu : "Bonjour Alice"



function estPair(nombre) {
  if (nombre % 2 === 0) {
    return ("true")
  }
    else {
      return ("false")
    }
}
console.log(estPair(4)); // Résultat attendu : true
console.log(estPair(7)); // Résultat attendu : false



function aireRectangle(longueur, largeur) {
  return longueur * largeur
}
console.log(aireRectangle(5, 3)); // Résultat attendu : 15




function estMajuscule(chaine) {
  if (chaine.toUpperCase === chaine) {
    return ("true")
  } else {
    return ("false")
  }
}
cestMajuscule("HELLO"); // Résultat attendu : true
estMajuscule("Hello"); // Résultat attendu : false





