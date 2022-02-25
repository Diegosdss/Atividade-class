class Quadrado {
  int base = 0;
  int altura = 0;

  int GetBase() {
    return this.base;
  }

  int GetAltura() {
    return this.altura;
  }

  void SetBase(int base) {
    this.base = base;
  }

  void SetAltura(int altura) {
    this.altura = altura;
  }

  int calcularArea() {
    return this.base = this.altura;
  }
}

void main() {
  Quadrado quadrado = Quadrado();

  quadrado.GetAltura();
  print(quadrado.altura);

  quadrado.SetAltura(5);
  print(quadrado.altura);

  quadrado.GetBase();
  print(quadrado.base);

  quadrado.SetBase(5);
  print(quadrado.base);

  print(quadrado.calcularArea());
}
