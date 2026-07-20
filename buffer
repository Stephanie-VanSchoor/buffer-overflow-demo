#include <stdio.h>
#include <string.h>

void fonction_secrete() {
    printf("🔥 ATTENTION ! Fonction secrète exécutée !\n");
}

void vulnerable(char *input) {
    char buffer[10];
    strcpy(buffer, input);
}

int main(int argc, char *argv[]) {
    if (argc < 2) {
        printf("Usage : %s <texte>\n", argv[0]);
        return 1;
    }
    
    printf("📥 Entrée : %s\n", argv[1]);
    vulnerable(argv[1]);
    printf("✅ Programme terminé.\n");
    return 0;
}
