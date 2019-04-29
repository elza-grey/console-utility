package com.company;

import java.io.FileNotFoundException;
import java.io.IOException;
import java.io.PrintWriter;
import java.nio.charset.Charset;
import java.nio.file.Files;
import java.nio.file.Path;
import java.nio.file.Paths;
import java.util.List;
import java.util.Scanner;


//запуск потоков
    public class Potock {
        public void main(String[] args) {
            for (int i = 0; i < 10; i++) {
                chisla();
            }
        }
    }
     public class Main {
     public void chisla() throws FileNotFoundException {
            Runnable runnable = new Runnable() {
                @Override
                public void run() throws IOException {
                
                /*Scanner scanner = new Scanner(System.in);
            String sring = scanner.nextLine();
         {  e.printStackTrace();
        }
    }
                */
                    List<String> lines = Files.readAllLines(Paths.get("input.txt"), Charset.defaultCharset());
                    //for (String x:lines) {
                    int a = Integer.parseInt(lines.get(0));
                    int b = Integer.parseInt(lines.get(1));
                    //}
                    int d = a + b;
                }

                //запись в файл
                String text = Integer.toString(d);
                PrintWriter out = new PrintWriter("output.txt");
        out.println(text);
        out.close();

            }
        }

               

            
