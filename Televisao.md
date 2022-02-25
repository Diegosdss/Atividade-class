void main(){
  Televisao televisao = Televisao();
  televisao.LigaDesliga();
  televisao.AumentaCanal();
  televisao.AumentaVolume();
  print(televisao.status);
  print(televisao.canal);
  print(televisao.volume);
}

class Televisao {
  bool status = true;
  int canal = 0;
  int volume = 0;

  Televisao(){
    this.status = false;
  }

  void LigaDesliga(){
    if(!this.status){
    this.canal = 3; 
    this.volume = 10;
    this.status = true;
    
    }
    else{
      this.status = !this.status;
    }
  }
  void AumentaCanal(){
    if(this.status){
      this.canal ++;
    }
}
void AumentaVolume(){
  if(this.status){
    this.volume ++;
  }
}
int MostraCanal(){
   return this.canal;
}
int MostraVolume(){
  return this.volume;
}

}
