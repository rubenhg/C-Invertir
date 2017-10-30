# C-Invertir
int main(int argc, char* argv[])
{
 char cadena[]="hola";
 char salida[25]={0};
 int largo, i, x;

 largo = strlen(cadena) - 1;
 for(i=largo, x=0; i >=0; i--, x++)
  salida[x]=cadena[i];
 printf("Palabra inicial: %s\nResultado: %s\n\n", cadena, salida);
 return 0;
}
