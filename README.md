int main()
{

    int i, b;
    int v[6] = {1, 0, 5, 2, 9, 7}; //A: jC! comeC'a dando os valores no vetor
    setlocale(LC_ALL, "Portuguese");
     for(i=0; i<5; i++){
            printf("%d ", v[i]);
     }
     
     //questão b
     b = 0;
     
     
     for(i=0; i<1; i++)
     {
     b = b+v[i];
     }
      
      
      for(i=1; i<1; i++)
     {
     b = b+v[i];
     }
      
     
      for(i=5; i<1; i++)
     {
     b = b+v[i];
     }
     printf("\n %d", b);
    
    return 0;
}
