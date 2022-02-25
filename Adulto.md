void main() {
  Adulto adulto = Adulto();
  print("O peso medido é: ");
  print(adulto.peso);

  print("ENGORDANDO...");

  adulto.Engordar(15);
  print(adulto.peso);

  adulto.Emagrecer(12);
  print(adulto.peso);
}

class Adulto {
  double peso = 100;
  double quilos = 0;

  void Engordar(double quilos) {
    this.quilos++;
    peso += quilos;
  }

  void Emagrecer(double quilos) {
    peso -= quilos;
  }
}
