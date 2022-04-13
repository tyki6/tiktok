# Liste des petits challenges donnés sur tiktok

# Challenge 1

Faire un programme qui retourne les 5 plus grands nombres d'une liste ordonné de maniere croisssante.

exemple:
```
ma_liste = [10, 67, 45, 33, 12, 98, 55]
resultat de max5(ma_liste) sera egal à [33, 45, 55, 67, 98]
```
## Python
```python
def max5(liste):
    liste.sort()
    return liste[-5:]
print(max5(ma_liste))
```
## Javascript
```javascript
function max5(liste) {
    return liste.sort.slice(-5)
}
console.log(max5(ma_liste))
```
## Rust
```rust
fn max5(liste: Vec<i32>) -> Vec<i32> {
    liste.sort();
    return &liste[..=4];
}
println!("{}", max5(ma_liste))
```