class Tripulante {
  String tipo = "Geraldao";

  String GetTipo() {
    return this.tipo;
  }

  void SetTipo(String tipo) {
    this.tipo = tipo;
  }
}

void main() {
  Tripulante tripulante = Tripulante();
  tripulante.GetTipo();
  print(tripulante.tipo);

  tripulante.SetTipo("da Portaria");
  print(tripulante.tipo);
}
