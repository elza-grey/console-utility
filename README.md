package com.company;

public class Main {

        try {
            Scanner scanner = new Scanner(System.in);
            String sring = scanner.nextLine();
             } catch (Exception e) {
            e.printStackTrace();
        }}
        
        //запуск потоков
        public class Potock {
    public static void main(String[] args) {
        for (int i = 0; i < 10; i++) {
            chisla();
            }}
            public static void chisla() {
        Runnable runnable = new Runnable() {
            @Override
            public void run() {
                int j;
                for (j = 0; j < 100; j++) {
                    System.out.println(j);
                }}
               //вывод на консоль
               

            
