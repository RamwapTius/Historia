public class Discord {

    public static void main(String[] args) {

        Discord projeto = new Discord();

        //P: representa a fala da professora
        //R: representa a fala do Rafael (personagem principal

        int horario = 7;
        String nome = "Rafael";
        System.out.println("Numa tarde de quinta-feira as " + horario + " horas da manha entrava na escola Sao Pedro um novo aluno chamado " + nome + " e era super tímido.\n");

        System.out.println("P: Qual é o seu nome? - Perguntou a professora");
        String nome1 = "Rafael";
        System.out.println("R: " + nome1);

        System.out.println("P: Quantos anos voce tem?");
        int idade = 17;
        System.out.println("R: " + idade);

        System.out.println("P: Voce pegou o seu novo uniforme pra entrar?");
        System.out.println("R: Sim\n ");

        System.out.println("P: Bem turma, pra quem nao sabe, esse é o nosso novo aluno, deem boas vindas a ele!");
        String nome3 = "Rafael!";
        System.out.println("Bem-vindo, " + nome3 + " - falou toda a turma.\n");

        String nome4 = "Rafael";
        System.out.println("Enfim o dia acabou e " + nome4 + " chegou em casa, jantou, tomou banho, jogou em seu compuitador e dormiu.\n");




                 //Capítulo 2


                //P: representa a fala da professora
               //R: representa a fala do Rafael (personagem principal
              //G: representa a fala do Gustavo (personagem adjuvante)

                System.out.println("No dia seguinte...\n");

        String professora = "Professora!";
        System.out.println("R: " + professora + " Voce tem certeza que passara as provas hoje?");

        int pontos = 15;
        String nome5 = "Rafael";
        String nomeg = "Gustavo";

        System.out.println("P: Tenho sim, e valerá " + pontos + " pontos!");
        System.out.println("R: Mas eu entrei na escola ontem e nao sei de nada da materia!");
        System.out.println("P: Deixa de frescura menino! Dá seus pulos, procura saber com seus colegas!\n");
        System.out.println("Neste momento " + nome5 + " percebeu que terá dificuldades em amigar com a professora, Mas como ele conseguirá a materia da prova sendo que ele nao tem ainda intimidade com seus novos colegas de sala?");
        System.out.println("Entao " + nome5 + " viu um menino sentado ao fundo da sala com fones no ouvido escutando música\n");

        System.out.println("R: Olá, posso falar com voce?");
        System.out.println("G: Pode sim.");
        System.out.println("R: Pode me dizer qual materia cairá na prova de hoje?");
        System.out.println("G: Será prova de história e vai cair sobre o governo de Getúlio Vargas.");
        System.out.println("R: Ah! Obrigado. Meu nome é " + nome5 + "! E o seu nome?");
        System.out.println("G: meu nome é " + nomeg + ". Mas as pessoas me chamam de gordinho. Nao gosto muito mas fazer o que...\n");

        System.out.println(nome5 + " enfim conseguiu saber a materia da prova, porém, já é muito tarde para comecar a estudar.\n");

        System.out.println("P: Bem turma, sentem em seus lugares que vou comecar a entregar as provas. - Disse a professora - Voces terao 1 hora pra fazer.\n");

        System.out.println("Toda turma comecou a reclamar do tempo de prova\n");

        System.out.println("P: SILENCIO! - Gritou a professora\n");
        System.out.println("G: Nao liga pra ela. A professora sempre foi assim. Estamos acostumados - Disse Gustavo para Rafael");
        System.out.println("R: Ah! Ok.\n");

        System.out.println("Todo mundo terminou a prova e todos entragram a avaliacao para a professora");
        System.out.println("Enfim, acabou as aulas e na saída a professora chamou " + nome5 + " para conversar\n");

        System.out.println("P: Aqui está o cronograma das provas desta semana.");
        System.out.println("R: Ah, obrigado.");
        System.out.println("P: E tem mais alguma coisa que eu queria dizer. Me desculpe se fui grossa com voce hoje. - A professora nao deu muito motivo do motivo para estar se desculpando");
        System.out.println("R: Ok.\n");

        System.out.println(nome5 + " entao pegou o cronograma e viu as datas das provas.\n");

        int dia = 3;
        String nomeDia;
        String história = "História";
        String matemática = "Matemática";
        String geografia = "Geografia";
        String física = "Física";
        String portugues = "Portugues";
        String biologia = "Biologia";
        String química = "Química";
        String ingles = "Ingles";
        String arte = "Arte";

        //Sabado 14 - Domingo 15

        switch (dia) {
            case 3:
                nomeDia = "Terca-feira - 10/06/2024";
                System.out.println(nomeDia);
                System.out.println(história+ "\n");

            case 4:
                nomeDia = "Quarta-feira - 11/06/2024";
                System.out.println(nomeDia);
                System.out.println(matemática+ "\n");
            case 5:
                nomeDia = "Quinta-feira - 12/06/2024";
                System.out.println(nomeDia);
                System.out.println(física+ "\n");

            case 6:
                nomeDia = "Sexta-feira 13/06/2024";
                System.out.println(nomeDia);
                System.out.println(ingles + "\n");

            case 12:
                nomeDia = "Segunda-feira - 16/06/2024";
                System.out.println(nomeDia);
                System.out.println(geografia+ "\n");

            case 13:
                nomeDia = "Terca-feira - 17/06/2024";
                System.out.println(nomeDia);
                System.out.println(portugues+ "\n");

            case 14:
                nomeDia = "Quarta-feira - 18/06/2024";
                System.out.println(nomeDia);
                System.out.println(biologia+ "\n");

            case 15:
                nomeDia = "Quinta-feira - 19/06/2024";
                System.out.println(nomeDia);
                System.out.println(química+ "\n");

            case 16:
                nomeDia = "Sexta-feira - 20/06/2024";
                System.out.println(nomeDia);
                System.out.println(arte+ "\n");
        }

        //Capítulo 3 | Em desenvolvimento.
    }
}
