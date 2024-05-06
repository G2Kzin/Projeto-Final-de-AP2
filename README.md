#include <stdio.h>
#include <string.h>
#include <locale.h>

#define RED   "\x1B[31m"
#define GRN   "\x1B[32m"
#define YEL   "\x1B[33m"
#define BLU   "\x1B[34m"
#define MAG   "\x1B[35m"
#define CYN   "\x1B[36m"
#define WHT   "\x1B[37m"
#define RESET "\x1B[0m"

int controle = 1;

    //acao
//struct uncharted
typedef struct uncharted{

        char filme[50];
        int lancado;
        char duracao[50];
        char onde[50];
};

//struct aquaman 2
typedef struct aquaman{

        char filme[50];
        int lancado;
        char duracao[50];
        char onde[50];
};

//struct vingadores
typedef struct vingadores{

        char filme[50];
        int lancado;
        char duracao[50];
        char onde[50];
};

//struct homem aranha
typedef struct aranha{

        char filme[50];
        int lancado;
        char duracao[50];
        char onde[50];
};

//struct batman
typedef struct batman{

        char filme[50];
        int lancado;
        char duracao[50];
        char onde[50];
};

//struct ninja assassino
typedef struct ninja{

        char filme[50];
        int lancado;
        char duracao[50];
        char onde[50];
};

    //ficcao
//struct distrito 9
typedef struct distrito{

        char filme[50];
        int lancado;
        char duracao[50];
        char onde[50];
};

//struct avatar
typedef struct avatar{

        char filme[50];
        int lancado;
        char duracao[50];
        char onde[50];
};

//struct wall-e
typedef struct wall{

        char filme[50];
        int lancado;
        char duracao[50];
        char onde[50];
};

//struct avatar 2
typedef struct avatar2{

        char filme[50];
        int lancado;
        char duracao[50];
        char onde[50];
};

//struct InterEstelar
typedef struct inter{

        char filme[50];
        int lancado;
        char duracao[50];
        char onde[50];
};

//struct mentes sombrias
typedef struct mentes{

        char filme[50];
        int lancado;
        char duracao[50];
        char onde[50];
};

    //comedia
//struct misterio em paris
typedef struct misterio{

        char filme[50];
        int lancado;
        char duracao[50];
        char onde[50];
};

//struct minha mae e uma peca
typedef struct mae{

        char filme[50];
        int lancado;
        char duracao[50];
        char onde[50];
};

//struct meu malvado favorito
typedef struct malvado{

        char filme[50];
        int lancado;
        char duracao[50];
        char onde[50];
};

//struct gente grande
typedef struct gente{

        char filme[50];
        int lancado;
        char duracao[50];
        char onde[50];
};

//struct familia do bagulho
typedef struct familia{

        char filme[50];
        int lancado;
        char duracao[50];
        char onde[50];
};

//struct deadpool
typedef struct deadpool{

        char filme[50];
        int lancado;
        char duracao[50];
        char onde[50];
};

    //romance
//struct foi apenas um sonho
typedef struct sonho{

        char filme[50];
        int lancado;
        char duracao[50];
        char onde[50];
};
//struct para sempre
typedef struct sempre{

        char filme[50];
        int lancado;
        char duracao[50];
        char onde[50];
};

//struct a cinco passos de voce
typedef struct passos{

        char filme[50];
        int lancado;
        char duracao[50];
        char onde[50];
};

//struct mais que amigos
typedef struct amigos{

        char filme[50];
        int lancado;
        char duracao[50];
        char onde[50];
};

//struct passengers
typedef struct passengers{

        char filme[50];
        int lancado;
        char duracao[50];
        char onde[50];
};

//struct a colina escarlate
typedef struct colina{

        char filme[50];
        int lancado;
        char duracao[50];
        char onde[50];
};

//funcao tela principal
void TelaPrincipal(){

    int i;

    printf("%c", 201);
    for(i=0; i <= 25; i++){
        printf("%c", 205);
    }
    printf("%c\n", 187);
    printf("%c", 186);

    printf("\t\t\t   %c                          \n%c", 186, 186);
    printf("     TELA PRINCIPAL       %c\n", 186);
    printf("%c                          %c\n", 186, 186);

    printf("%c", 200);
    for(i=0; i <= 25; i++){
        printf("%c", 205);
    }
    printf("%c\n", 188);

    printf("Catalogo \n\n");

    printf("avalie a sua experiencia no App \n\n");

    printf("Favoritos \n\n");

    printf("Sair do app \n \n");

}

//funcao loguin de usuario
void login(){

    int i;
    char user[50];
    char senha[50];

    printf("%c", 201);
    for(i=0; i <= 25; i++){
        printf("%c", 205);
    }
    printf("%c\n", 187);
    printf("%c", 186);

    printf("\t\t\t   %c                          \n%c", 186, 186);
    printf("     LOGIN DE USUARIO     %c\n", 186);
    printf("%c                          %c\n", 186, 186);

    printf("%c", 200);
    for(i=0; i <= 25; i++){
        printf("%c", 205);
    }
    printf("%c\n", 188);

    //digitar usuario
    printf("Insira seu email: " CYN);
    scanf("%[^\n]s", &user);
    printf("\n");
    fflush(stdin);

    //digitar senha
    printf(RESET "Digite a senha: " CYN);
    scanf("%[^\n]s", &senha);
    printf("\n");
    printf(RESET "\n");

}

//funcao usuario novo
void userNew(){

    char usern[50];
    char email[50];
    char senhan[50];
    char nomenew[50];
    int i;

        printf("%c", 201);
    for(i=0; i <= 25; i++){
        printf("%c", 205);
    }
    printf("%c\n", 187);
    printf("%c", 186);

    printf("\t\t\t   %c                          \n%c", 186, 186);
    printf("       USUARIO NOVO       %c\n", 186);
    printf("%c                          %c\n", 186, 186);

    printf("%c", 200);
    for(i=0; i <= 25; i++){
        printf("%c", 205);
    }
    printf("%c\n", 188);
    printf("Para comecar insira seus dados \n");

    printf("Qual o seu nome: " CYN);
    scanf("%[^\n]s", &usern);
    printf("\n");
    fflush(stdin);

    printf(RESET "digite seu email: " CYN);
    scanf("%s", &email);
    printf("\n");
    fflush(stdin);

    printf(RESET "Senha: " CYN);
    scanf("%[^\n]s", &senhan);
    printf(RESET "\n");
    fflush(stdin);
    system("cls");

    printf("bem vindo ");
    printf(GRN "%s", usern);
    printf(RESET "\n");
}
// funcao favoritos
void favoritos(){
    FILE *arq_txt;

    int i;
    char op[10];
    char filmeAdc[50];
    char caractere;

    if(arq_txt == NULL){
        printf("erro na abertura");
    }

    printf("- Adicionar um novo filme aos favoritos. \n");
    printf("\n");
    printf("- Ver os filmes favoritos. \n");
    scanf("%s", &op);
    system("cls");

    //adicionar favoritos
    if(strcmp(op, "adicionar") == 0){
        arq_txt = fopen("favoritos.txt", "a");
        printf("Qual filme deseja favoritar: \n");
        fflush(stdin);
        fgets(filmeAdc, sizeof(filmeAdc), stdin);

        fprintf(arq_txt, "\n%s", filmeAdc);

        fclose(arq_txt);

        printf("Filme adicionado.\n");
        system("pause");
        system("cls");


    // ver favoritos
    }else if(strcmp(op, "ver") == 0){
        fflush(stdin);
        arq_txt = fopen("favoritos.txt", "r");

        while ((caractere = fgetc(arq_txt)) != EOF) {
            printf("%c", caractere);
        }
        printf("\n");

    system("pause"),
    system("cls");

        fclose(arq_txt);
    }

}

// funcao avaliar
void avaliacao(){

    int ava;
    int estrela, estrela2;

    printf("gostaria de avaliar o Aplicativo?\n");
    printf("(1) sim \n");
    printf("(2) nao \n");
    scanf("%d", &ava);

    switch(ava){

case 1:

    printf("adicione uma avaliacao de 1 a 5: ");
    scanf("%d", &estrela);
    system("cls");

    trocavalor(&estrela, &estrela2);

    printf("sua nota foi de  ");
    printf(RED "%d \n", estrela2);
    printf(RESET "avalicao salvada. \n\n");

    system("pause");
    system("cls");

    break;

default:

    printf("voltando a tela inicial...\n");

    system("pause");
    system("cls");

    break;

    }
}

//funcao passagem por prametros
void trocavalor(int *a, int *b){

    int troca = *a;
    *a = *b;
    *b = troca;

}

//funcao catalogo
void catalogo(){

//acao
    //declaracao uncharted1
    struct uncharted uncharted1 = {"uncharted", 2022, "1hr 52min", "Amazon Prime"};

    //declaracao aquaman 2
    struct aquaman aquaman1 = {"aquaman 2", 2023, "1hr 55min", "Amazon Prime"};

    //declaracao vingadores
    struct vingadores vingadores1 = {"vingadores: Ultimato", 2019, "3hr 20min", "Disney+"};

    //declaracao homem aranha
    struct aranha aranha1 = {"Homem-Aranha: No Way Home", 2021, "2hr 28min", "Amazon Prime"};

    //declaracao Batman: O Cavaleiro das Trevas
    struct batman batman1 = {"Batman: O Cavaleiro das Trevas", 2008, "2hr 32min", "HBO MAX"};

    //declaracao ninja assassino
    struct ninja ninja1 = {"Ninja Assassino", 2009, "1hr 39min", "HBO MAX"};

//ficcao
    //declaracao distrito 9
    struct distrito distrito9 = {"Distrito 9", 2009, "1hr 52min", "Amazon Prime"};

    //declaracao avatar
    struct avatar avatar1 = {"Avatar", 2009, "2hr 42min", "Diney+"};

    //declaracao wall-e
    struct wall wall1 = {"Wall-E", 2009, "1hr 43min", "Disney+"};

    //declaracao avatar 2
    struct avatar2 avatar2 = {"Avatar 2", 2022, "3hr 21min", "Disney+"};

    //declaracao InterEstelar
    struct inter inter1 = {"InterEstelar", 2014, "2hr 49min", "Amazon Prime"};

    //declaracao Mentes Sombrias
    struct mentes mentes1 = {"Mentes Sombrias", 2018, "1hr 45min", "Star+"};

//comedia
    //declaracao misterio em paris
    struct misterio misterio1 = {"Misterio em Paris", 2023, "1hr 29min", "NetFlix"};

    //declaracao Minha mae e uma peca
    struct mae mae1 = {"Minha Mae e uma Peca", 2013, "1hr 24min", "NetFlix"};

    //declaracao Meu Malvado favorito
    struct malvado malvado1 = {"Meu Malvado Favorito", 2010, "1hr 23min", "NetFlix"};

    //declaracao gente grande
    struct gente gente1 = {"Gente Grande", 2010, "1hr 45min", "NetFlix"};

    //declaracao familia do bagulho
    struct familia familia1 = {"Familia do bagulho", 2013, "1hr 50min", "Amazon Prime"};

    //declaracao DeadPool
    struct deadpool deadpool1 = {"DeadPool", 2016, "1hr 48min", "disney+"};

//romance
    //declaracao foi apenas um sonho
    struct sonho sonho1 = {"Foi Apenas Um Sonho", 2008, "2hr 05min", "Amazon Prime"};

    //declaracao Para Sempre
    struct sempre sempre1 = {"Para Sempre", 2012, "1hr 44min", "Amazon Prime"};

    //declaracao a cinco passos de voce
    struct passos passos1 = {"a cinco passos de voce", 2019, "1hr 57min", "NEtFlix"};

    //declaracao mais que amigos
    struct amigos amigos1 = {"Mais que Amigos", 2022, "1hr 55min", "TeleCine"};

    //declaracao a colina escarlate
    struct colina colina1 = {"A Colina Escarlate", 2015, "1hr 59min", "Apple TV"};

    //declaracao passangers
    struct passengers passengers1 = {"Passangers", 2016, "1hr 56min", "NetFlix"};

    int genero;
    char filmeAcao[50];
    char filmeFic[50];
    char filmeComed[50];
    char filmeRom[50];

    //escolher genero
    printf("bem vindo ao nosso catalogo.\n\n");
    printf("quer acessa qual genero? \n");
    printf("(1) Acao\n");
    printf("(2) ficcao\n");
    printf("(3) comedia\n");
    printf("(4) Romance\n");
    scanf("%d", &genero);

    system("cls");
    fflush(stdin);

    switch(genero){

        //case de acao
        case 1:

            printf(GRN "Catalogo de Acao: \n\n" RESET);

            printf("Uncharted \t\t Aquaman 2 \n\n");
            printf("Vingadores: Ultimato \t Homem-Aranha: no Way Home \n\n");
            printf("Batman \t\t\t Ninja Assasino \n\n");
            scanf("%50[^\n]s", &filmeAcao);
            system("cls");

            if(strcmp(filmeAcao, "uncharted") == 0){

                printf("Filme: %s \n\n", uncharted1.filme);
                printf("Lancado em: %d\n\n", uncharted1.lancado);
                printf("Duracao: %s\n\n", uncharted1.duracao);
                printf("Disponivel em: %s \n\n", uncharted1.onde);

            }else if(strcmp(filmeAcao, "aquaman 2") == 0){

                printf("Filme: %s \n\n", aquaman1.filme);
                printf("Lancado em: %d\n\n", aquaman1.lancado);
                printf("Duracao: %s\n\n", aquaman1.duracao);
                printf("Disponivel em: %s \n\n", aquaman1.onde);

            }else if(strcmp(filmeAcao, "vingadores") == 0){

                printf("Filme: %s \n\n", vingadores1.filme);
                printf("Lancado em: %d\n\n", vingadores1.lancado);
                printf("Duracao: %s\n\n", vingadores1.duracao);
                printf("Disponivel em: %s \n\n", vingadores1.onde);

            }else if(strcmp(filmeAcao, "homem aranha") == 0){

                printf("Filme: %s \n\n", aranha1.filme);
                printf("Lancado em: %d\n\n", aranha1.lancado);
                printf("Duracao: %s\n", aranha1.duracao);
                printf("Disponivel em: %s \n\n", aranha1.onde);

            }else if(strcmp(filmeAcao, "batman") == 0){

                printf("Filme: %s \n\n", batman1.filme);
                printf("Lancado em: %d\n\n", batman1.lancado);
                printf("Duracao: %s\n\n", batman1.duracao);
                printf("Disponivel em: %s \n\n", batman1.onde);

            }else if(strcmp(filmeAcao, "ninja") == 0){

                printf("Filme: %s \n\n", ninja1.filme);
                printf("Lancado em: %d\n\n", ninja1.lancado);
                printf("Duracao: %s\n\n", ninja1.duracao);
                printf("Disponivel em: %s \n\n", ninja1.onde);

            }else{
                printf("escolha invalida. \n");
            }

            break;

        // case de ficcao
        case 2:

            printf(GRN "Catalogo de Ficcao: \n\n" RESET);

            printf("Distrito 9 \t\t Avatar \n\n");
            printf("Wall-E \t\t\t Avatar 2 \n\n");
            printf("InterEstelar \t\t Mentes Sombrias \n\n");
            scanf("%50[^\n]s", &filmeFic);
            system("cls");

            if(strcmp(filmeFic, "distrito 9") == 0){

                printf("Filme: %s \n\n", distrito9.filme);
                printf("Lancado em: %d\n\n", distrito9.lancado);
                printf("Duracao: %s\n\n", distrito9.duracao);
                printf("Disponivel em: %s \n\n", distrito9.onde);

            }else if(strcmp(filmeFic, "avatar") == 0){

                printf("Filme: %s \n\n", avatar1.filme);
                printf("Lancado em: %d\n\n", avatar1.lancado);
                printf("Duracao: %s\n\n", avatar1.duracao);
                printf("Disponivel em: %s \n\n", avatar1.onde);

            }else if(strcmp(filmeFic, "wall-e") == 0){

                printf("Filme: %s \n\n", wall1.filme);
                printf("Lancado em: %d\n\n", wall1.lancado);
                printf("Duracao: %s\n\n", wall1.duracao);
                printf("Disponivel em: %s \n\n", wall1.onde);

            }else if(strcmp(filmeFic, "avatar 2") == 0){

                printf("Filme: %s \n\n", avatar2.filme);
                printf("Lancado em: %d\n\n", avatar2.lancado);
                printf("Duracao: %s\n\n", avatar2.duracao);
                printf("Disponivel em: %s \n\n", avatar2.onde);

            }else if(strcmp(filmeFic, "interestelar") == 0){

                printf("Filme: %s \n\n", inter1.filme);
                printf("Lancado em: %d\n\n", inter1.lancado);
                printf("Duracao: %s\n\n", inter1.duracao);
                printf("Disponivel em: %s \n\n", inter1.onde);

            }else if(strcmp(filmeFic, "mentes sombrias") == 0){

                printf("Filme: %s \n\n", mentes1.filme);
                printf("Lancado em: %d\n\n", mentes1.lancado);
                printf("Duracao: %s\n\n", mentes1.duracao);
                printf("Disponivel em: %s \n\n", mentes1.onde);

            }else{
                printf("escolha invalida. \n");
            }

            break;

        case 3:

            printf(GRN "Catalogo de Comedia: \n\n" RESET);

            printf("Misterio Em Paris \t Minha mae e um peca \n\n");
            printf("Meu Malvado Favorito \t Gente Grande \n\n");
            printf("Familia do Bagulho \t DeadPool \n\n");
            scanf("%50[^\n]s", &filmeComed);
            system("cls");

            if(strcmp(filmeComed, "misterio em paris") == 0){

                printf("Filme: %s \n\n", misterio1.filme);
                printf("Lancado em: %d\n\n", misterio1.lancado);
                printf("Duracao: %s\n\n", misterio1.duracao);
                printf("Disponivel em: %s \n\n", misterio1.onde);

            }else if(strcmp(filmeComed, "minha mae e uma peca") == 0){

                printf("Filme: %s \n\n", mae1.filme);
                printf("Lancado em: %d\n\n", mae1.lancado);
                printf("Duracao: %s\n\n", mae1.duracao);
                printf("Disponivel em: %s \n\n", mae1.onde);

            }else if(strcmp(filmeComed, "meu malvado favorito") == 0){

                printf("Filme: %s \n\n", malvado1.filme);
                printf("Lancado em: %d\n\n", malvado1.lancado);
                printf("Duracao: %s\n\n", malvado1.duracao);
                printf("Disponivel em: %s \n\n", malvado1.onde);

            }else if(strcmp(filmeComed, "gente grande") == 0){

                printf("Filme: %s \n\n", gente1.filme);
                printf("Lancado em: %d\n\n", gente1.lancado);
                printf("Duracao: %s\n\n", gente1.duracao);
                printf("Disponivel em: %s \n\n", gente1.onde);

            }else if(strcmp(filmeComed, "familia do bagulho") == 0){

                printf("Filme: %s \n\n", familia1.filme);
                printf("Lancado em: %d\n\n", familia1.lancado);
                printf("Duracao: %s\n\n", familia1.duracao);
                printf("Disponivel em: %s \n\n", familia1.onde);

            }else if(strcmp(filmeComed, "deadpool") == 0){

                printf("Filme: %s \n\n", deadpool1.filme);
                printf("Lancado em: %d\n\n", deadpool1.lancado);
                printf("Duracao: %s\n\n", deadpool1.duracao);
                printf("Disponivel em: %s \n\n", deadpool1.onde);

            }else{
                printf("escolha invalida. \n");
            }

            break;

        case 4:

            printf(GRN "Catalogo de Romance: \n\n" RESET);

            printf("Foi Apenas um Sonho \t Para Sempre \n\n");
            printf("A cinco passos de voce \t Mais que Amigos \n\n");
            printf("A colina Escarlate \t Passengers \n\n");
            scanf("%50[^\n]s", &filmeRom);
            system("cls");

            if(strcmp(filmeRom, "foi apenas um sonho") == 0){

                printf("Filme: %s \n\n", sonho1.filme);
                printf("Lancado em: %d\n\n", sonho1.lancado);
                printf("Duracao: %s\n\n", sonho1.duracao);
                printf("Disponivel em: %s \n\n", sonho1.onde);

            }else if(strcmp(filmeRom, "para sempre") == 0){

                printf("Filme: %s \n\n", sempre1.filme);
                printf("Lancado em: %d\n\n", sempre1.lancado);
                printf("Duracao: %s\n\n", sempre1.duracao);
                printf("Disponivel em: %s \n\n", sempre1.onde);

            }else if(strcmp(filmeRom, "a cinco passos de voce") == 0){

                printf("Filme: %s \n\n", passos1.filme);
                printf("Lancado em: %d\n\n", passos1.lancado);
                printf("Duracao: %s\n\n", passos1.duracao);
                printf("Disponivel em: %s \n\n", passos1.onde);

            }else if(strcmp(filmeRom, "mais que amigos") == 0){

                printf("Filme: %s \n\n", amigos1.filme);
                printf("Lancado em: %d\n\n", amigos1.lancado);
                printf("Duracao: %s\n\n", amigos1.duracao);
                printf("Disponivel em: %s \n\n", amigos1.onde);

            }else if(strcmp(filmeRom, "a colina escarlate") == 0){

                printf("Filme: %s \n\n", colina1.filme);
                printf("Lancado em: %d\n\n", colina1.lancado);
                printf("Duracao: %s\n\n", colina1.duracao);
                printf("Disponivel em: %s \n\n", colina1.onde);

            }else if(strcmp(filmeRom, "passengers") == 0){

                printf("Filme: %s \n\n", passengers1.filme);
                printf("Lancado em: %d\n\n", passengers1.lancado);
                printf("Duracao: %s\n\n", passengers1.duracao);
                printf("Disponivel em: %s \n\n", passengers1.onde);

            }else{
                printf("escolha invalida. \n");
            }

            break;

        default:
            printf("catalogo invalido. \n");
    }


    system("pause");
    system("cls");
}

//Função recursiva para perguntar ao usuário se deseja sair
void perguntarSair(){

    char resposta[10];

    printf("Deseja sair do aplicativo? (s/n): ");
    scanf("%s", &resposta);

    if(strcmp(resposta, "sim") == 0){
        printf("Saindo do aplicativo...\n");
        printf(RED "\nObrigado por usar o App! \n" RESET);
        controle = controle + 1;
        return;

    }else if(strcmp(resposta, "nao") == 0){
        printf("\n voltando para atela inicial...\n");
        system("pause");
        system("cls");

    }else{
        printf("Entrada invalida. Por favor, responda com 'sim' para sair ou 'nao' para continuar.\n");
        perguntarSair();
    }
}

int main(){

    int i;
    char decisao[10];
    char avanca[15];
    char escolhaFinal[10];

    printf("%c", 201);
    for(i=0; i <= 30; i++){
        printf("%c", 205);
    }
    printf("%c\n", 187);
    printf("%c", 186);

    printf("\t\t\t\t%c                  \n%c", 186, 186);
    printf("   BEM VINDO AO SELECT MOVIE   %c\n", 186);
    printf("%c                               %c\n", 186, 186);

    printf("%c", 200);
    for(i=0; i <= 30; i++){
        printf("%c", 205);
    }
    printf("%c\n", 188);
    printf("\n");

    printf("Voce ja possui um conta? \n");
    scanf("%[^\n]s", &decisao);
    fflush(stdin);

    if(strcmp(decisao, "sim") == 0){
        system("cls");
        login();
    }else{
        system("cls");
        userNew();
    }

    printf("Login feito com sucesso. \n");
    system("pause");
    system("cls");

    //tela inicial

//para voltar a tela inicial
do{
    TelaPrincipal();

    scanf("%s", &avanca);
    system("cls");

    if(strcmp(avanca, "catalogo") == 0){

        printf("%c", 201);
        for(i=0; i <= 25; i++){
            printf("%c", 205);
        }
        printf("%c\n", 187);
        printf("%c", 186);

        printf("\t\t\t   %c                          \n%c", 186, 186);
        printf("       CATALOGO           %c\n", 186);
        printf("%c                          %c\n", 186, 186);

        printf("%c", 200);
        for(i=0; i <= 25; i++){
            printf("%c", 205);
        }
        printf("%c\n", 188);

        catalogo();

    }else if(strcmp(avanca, "avalie") == 0){

        printf("%c", 201);
        for(i=0; i <= 25; i++){
            printf("%c", 205);
        }
        printf("%c\n", 187);
        printf("%c", 186);

        printf("\t\t\t   %c                          \n%c", 186, 186);
        printf("        AVALIE O APP      %c\n", 186);
        printf("%c                          %c\n", 186, 186);

        printf("%c", 200);
        for(i=0; i <= 25; i++){
            printf("%c", 205);
        }
        printf("%c\n", 188);

        avaliacao();

    }else if(strcmp(avanca, "favoritos") == 0){

        printf("%c", 201);
        for(i=0; i <= 25; i++){
            printf("%c", 205);
        }
        printf("%c\n", 187);
        printf("%c", 186);

        printf("\t\t\t   %c                          \n%c", 186, 186);
        printf("        FAVORITOS         %c\n", 186);
        printf("%c                          %c\n", 186, 186);

        printf("%c", 200);
        for(i=0; i <= 25; i++){
            printf("%c", 205);
        }
        printf("%c\n", 188);

        favoritos();

    }else if(strcmp(avanca, "sair") == 0){

        printf("%c", 201);
        for(i=0; i <= 25; i++){
            printf("%c", 205);
        }
        printf("%c\n", 187);
        printf("%c", 186);

        printf("\t\t\t   %c                          \n%c", 186, 186);
        printf("      SAIR DO APP         %c\n", 186);
        printf("%c                          %c\n", 186, 186);

        printf("%c", 200);
        for(i=0; i <= 25; i++){
            printf("%c", 205);
        }
        printf("%c\n", 188);

        perguntarSair();

    }else{
        printf("%c", 201);
        for(i=0; i <= 25; i++){
            printf("%c", 205);
        }
        printf("%c\n", 187);
        printf("%c", 186);

        printf("\t\t\t   %c                          \n%c", 186, 186);
        printf("    ESCOLHA INVALIDA      %c\n", 186);
        printf("%c                          %c\n", 186, 186);

        printf("%c", 200);
        for(i=0; i <= 25; i++){
            printf("%c", 205);
        }
        printf("%c\n", 188);
    }

}while(controle < 2);

}
