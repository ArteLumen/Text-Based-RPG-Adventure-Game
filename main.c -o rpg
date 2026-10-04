#include <stdio.h>

int main() {
    int choice;
    int health = 100;
    int gold = 0;

    printf("=== DARK CAVE: TEXT-BASED RPG ===\n");
    printf("You are standing at the entrance of a dark cave. Your adventure begins...\n\n");

    printf("1. Sneak quietly into the cave.\n");
    printf("2. Build a campfire outside and wait until morning.\n");
    printf("Your choice (1 or 2): ");
    scanf("%d", &choice);

    if (choice == 1) {
        printf("\nIt is very dark inside! You stepped into a trap and lost 20 health.\n");
        health -= 20;
        printf("Remaining Health: %d\n\n", health);
    } else {
        printf("\nYou woke up well-rested. Your energy is full!\n\n");
    }

    printf("At the end of the path, a wild Goblin appears!\n");
    printf("1. Fight the Goblin.\n");
    printf("2. Run away from the Goblin.\n");
    printf("Your choice (1 or 2): ");
    scanf("%d", &choice);

    if (choice == 1) {
        printf("\nYou bravely defeated the Goblin! You earned 50 gold as a reward.\n");
        gold += 50;
    } else {
        printf("\nYou tripped while running away, but managed to escape safely (No reward).\n");
    }

    printf("\n==============================\n");
    printf("GAME OVER!\n");
    printf("Final Health: %d\n", health);
    printf("Total Gold Collected: %d\n", gold);
    printf("==============================\n");

    return 0;
}
