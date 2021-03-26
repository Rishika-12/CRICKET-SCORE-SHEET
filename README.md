# CRICKET-SCORE-SHEET
#include <stdio.h>

#include <dos.h>

#include <windows.h>

#include <winbase.h>

#include <conio.h>

#include <time.h>

#include <string.h>

#include"declaration.h"

#include"welcome.h"

#include"menu.h"

#include"newscoresheet.h"

int main(){

  int a,key;

  char b;

  File *fnew;

  char lastinput;

  while(TRUE){

    welcome();

    system("cls");

    menu();

    ch=getch();

    char ch;

    switch(ch){

      case'1':

      fileopen(ch);

      case'2':

      fileopen(ch);

      getch();

      case'3':

      system("cls");

      exit(0);

    }

  }

}

void welcome(){

   

}

void menu(){

  printf("\n\n\t\tMENU:\n\n");

  printf("\n\n1.NEW SCORE SHEET\n\n");

  printf("\n\n2.VIEW SCORE SHEET\n\n");

  printf("\n\n3.EXIT\n\n");

}

void date():

void printt():

void filewrite():

void fileopen(char):

void limitinput():

void newscoresheet(){

   

}
