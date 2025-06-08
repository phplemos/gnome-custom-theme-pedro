### **Conteúdo do Repositório**

- `openbar_pedro_theme`: Este arquivo contém as configurações específicas do OpenBar Extension.
- `gnome-full-backup.dconf`: Este arquivo contém um backup completo de todas as configurações do `dconf` do meu ambiente GNOME (incluindo temas, fontes, atalhos, etc.), exportado do caminho `/`. _Use com cautela, como explicado abaixo._

---

### **Como Usar Este Backup**

#### 1. Restaurando Configurações de Extensões

1.  **Clone o Repositório:**

    ```bash
    git clone https://github.com/phplemos/gnome-custom-theme-pedro
    cd gnome-custom-theme-pedro
    ```

2.  **Instale as Extensões:** Certifique-se de que as extensões que você deseja restaurar já estão instaladas na sua nova máquina. Você pode instalá-las manualmente através do site [GNOME Extensions](https://extensions.gnome.org/) ou pelo aplicativo "Extensões" da sua distribuição.

3.  **Importe as Configurações:**

    ```bash
    dconf load / < gnome-full-backup.dconf
    ```

4.  **Reinicie o GNOME Shell:** Para que as alterações surtam efeito, pressione `Alt + F2`, digite `r` (minúsculo) e pressione `Enter`.



### **Compatibilidade**

Este backup foi gerado no **GNOME 48**. A importação para outras versões do GNOME pode resultar em comportamento inesperado. É sempre recomendado fazer backups separados para cada versão principal do GNOME que você utiliza.

---
