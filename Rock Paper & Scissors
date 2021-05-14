package com.company;
import java.util.Random;
import java.util.Scanner;

public class Main {

    public static void main(String[] args) {
        Scanner input = new Scanner(System.in);
        Random roll = new Random();

                String[] dice_roll = new String[]{"1", "2", "3", "4", "5", "6"};
                int Roll = roll.nextInt(dice_roll.length);
                System.out.println("The dice has rolled a " + dice_roll[Roll] + " !!!\n");

                final int Rock = 1, Paper = 2, Scissor = 3;
                final String ch;
                int p1 = 0, p2 = 0;

        System.out.println("Press and enter R to roll the dice OR Q to quit");
        ch = input.next();
        switch(ch) {
            case "R":
                System.out.println("         |||| ROCK, PAPERS & SCISSORS ||||");
                for (int i = 0; i <= Roll; i++) {
                    System.out.println("Player 1:Choose [1]Rock, [2]Paper or [3]Scissors: ");
                    int player1 = input.nextInt();
                    System.out.println("Player 2:Choose [1]Rock, [2]Paper or [3]Scissors: ");
                    int player2 = input.nextInt();

                    if (player1 == player2) {
                        System.out.println("It is a tie !\n");
                    } else {
                        switch (player1) {
                            case Rock:
                                if (player2 == Paper) {
                                    System.out.println("Player 2 wins !\n");
                                    p1++;
                                } else {
                                    System.out.println("Player 1 wins !\n");
                                    p2++;
                                }
                                break;

                            case Paper:
                                if (player2 == Scissor) {
                                    System.out.println("Player 2 wins !\n");
                                    p1++;
                                } else {
                                    System.out.println("Player 1 wins !\n");
                                    p2++;
                                }
                                break;

                            case Scissor:
                                if (player2 == Rock) {
                                    System.out.println("Player 2 wins !\n");
                                    p1++;
                                } else {
                                    System.out.println("Player 1 wins !\n");
                                    p2++;
                                }
                                break;

                        }
                    }
                }

                System.out.println("\n         $$$$ SCOREBOARD $$$$");
                System.out.println("\n       Number of rounds played: " + (Roll + 1));
                System.out.println("        ||Vvv TOTAL SCORE vvV||");
                System.out.println("       Player 1: Has won " + p1 + " times");
                System.out.println("       Player 2: Has won " + p2 + " times");
                if (p1 > p2)
                    System.out.println("\n     Player 1 has won the whole game !");
                else if (p2 > p1)
                    System.out.println("\n     Player 2 has won the whole game !");
                else
                    System.out.println("\n            It's a tie !");

            case "Q":
                break;
        }
    }
}
