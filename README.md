## Hi there 👋

# 👨‍💻 Sobre mim

```java
public class Desenvolvedor {
    private String nome = "Ane";
    private String area = "Ciência da Computação";
    private String linguagemFavorita = "Java";
    private boolean viciadoEmCafe = true;

    public void rotinaDiaria() {
        while (true) {
            estudar();
            programar();
            compilar();
            estudoAutonomo();
            if (bugEncontrado()) {
                debugar();
            } else {
                System.out.println("Código funcionando! 🚀");
            }
        }
    }

    private void estudar() {
        System.out.println("📚 Atualmente no 2° período em: " + area);
    }

    private void programar() {
        System.out.println("☕ Codando em " + linguagemFavorita);
    }

    private void estudoAutonomo() {
        System.out.println("🔧 Python, AWS, JavaScript");
    }

    public static void main(String[] args) {
        Desenvolvedor eu = new Desenvolvedor();
        eu.rotinaDiaria();
    }
}

