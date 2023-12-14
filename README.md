#include <stdio.h>

int main() {
    float uzunKenar, kisaKenar, cevre;

    // Kullanıcıdan uzun kenar ve kısa kenar uzunluklarını al
    printf("Uzun kenar uzunlugunu girin: ");
    scanf("%f", &uzunKenar);

    printf("Kisa kenar uzunlugunu girin: ");
    scanf("%f", &kisaKenar);

    // Dikdörtgenin çevresini hesapla
    cevre = 2 * (uzunKenar + kisaKenar);

    // Sonucu ekranda göster
    printf("Dikdortgenin cevresi: %.2f\n", cevre);

    return 0;
}
