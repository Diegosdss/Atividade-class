class Voo {
  int codigo = 0;
  String? origem = "";
  String? destino = "";

  int GetCodigo() {
    return this.codigo;
  }

  void SetCodigo(int codigo) {
    this.codigo = codigo;
  }

  void SetOrigem(String origem) {
    this.origem = origem;
  }

  String? GetDestino() {
    return this.destino;
  }

  void SetDestino(String destino) {
    this.destino = destino;
  }
}

void main() {
  Voo voo = Voo();

  voo.GetCodigo();
  print(voo.codigo);
  voo.SetCodigo(9);
  print(voo.codigo);

  voo.SetOrigem("EASY");
  print(voo.origem);

  voo.GetDestino();
  print(voo.destino);

  voo.SetDestino("GG");
  print(voo.destino);
}
