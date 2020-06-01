

```js no-beautify
5 > 4 → true
"apple" > "pineapple" → false
"2" > "12" → true
undefined == null → true
undefined === null → false
null == "\n0\n" → false
null === +"\n0\n" → false
```

Algunas de las razones:

<<<<<<< HEAD:1-js/02-first-steps/08-comparison/1-comparison-questions/solution.md
1. Obviamente, true.
2. Comparación lexicográfica, por lo tanto false.
3. Una vez más, la comparación lexicográfica, el primer carácter de `"2"` es mayor que el primer carácter de `"1"`.
4. Los valores `null` y `undefined` son iguales entre sí solamente.
5. La igualdad estricta es estricta. Diferentes tipos de ambos lados conducen a false.
6. Ver (4).
7. Igualdad estricta de diferentes tipos.
=======
1. Obviously, true.
2. Dictionary comparison, hence false. `"a"` is smaller than `"p"`.
3. Again, dictionary comparison, first char of `"2"` is greater than the first char of `"1"`.
4. Values `null` and `undefined` equal each other only.
5. Strict equality is strict. Different types from both sides lead to false.
6. Similar to `(4)`, `null` only equals `undefined`.
7. Strict equality of different types.
>>>>>>> 69e44506c3e9dac74c282be37b55ba7ff122ae74:1-js/02-first-steps/09-comparison/1-comparison-questions/solution.md