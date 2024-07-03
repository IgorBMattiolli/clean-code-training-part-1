# clean-code-training-part-1

Nomes significativos

Exercício 01

Renomeie as variáveis e funções no código abaixo para terem nomes significativos conforme o seguinte contexto: Uma escola possui duas provas por semestre, então para facilitar o calcula da média de cada aluno foi desenvolvido um sistema para automatizar esse processo

```
const f = (x, y) => {
  const a = x + y;
  const b = a / 2;
  return b;
};

const result = f(10, 20);
console.log(result);
```

Exercício 02

Renomeie as variáveis e classes no código abaixo para terem nomes significativos conforme o seguinte contexto: A StartSe promoveu cinco eventos ao longo do ano, e o líder da área de eventos solicitou ao time de tecnologia um sistema que calculasse o total de participantes de todos os eventos.

```
class C {
    m(l: number[]): number {
        let r = 0;
        for (const i of l) {
            r += i;
        }
        return r;
    }
}

const c = new C();
const result = c.m([151, 829, 317, 147, 56]);
console.log(result);
```
Exercício 03

O código abaixo tem nomes pouco descritivos. Reescreva o código com nomes significativos para a classe e variáveis .

```
class P {
    p(d: { [key: string]: number }): number {
        let p = 1;
        for (const v of Object.values(d)) {
            p *= v;
        }
        return p;
    }
}

const data = { a: 1, b: 2, c: 3 };
const p = new P();
console.log(p.p(data));
```
