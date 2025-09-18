## Oi Oi 👋

# 👩‍💻 Sobre mim

```java
import java.util.*;
public class Desenvolvedora {
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
        System.out.println("🔧 Aprendendo por conta própria: Python, JavaScript, AWS");
    }

    private boolean bugEncontrado() {
        return Math.random() < 0.5;
    }

    private void debugar() {
        System.out.println("🐞 Bug encontrado! Iniciando o processo de debug...");
    }

    public static void main(String[] args) {
        Desenvolvedora eu = new Desenvolvedora();
        eu.rotinaDiaria();
    }
}

