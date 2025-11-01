# my-seventeenth-repo
seventeenth
function isPrime(n) {
  if (n < 2) return false;
  for (let i = 2; i <= Math.sqrt(n); i++) {
    if (n % i === 0) return false;
  }
  retur true;
}

console.log(isPrime(17));
