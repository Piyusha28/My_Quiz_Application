# My_Quiz_Application

package com.example.myquiz_application;

public class QuestionAnswer {

    public static String question[] ={
            "What is the Number of bit used by IPv6 address?",
            "Which one is the first web browser invented in 1990?",
            "What is the first Computer Virus?",
            "Firewall in computer is used for which purpose?",
            "Which one programming language is exclusively used for AI?"
    };

    public static String choices[][] = {
            {"32 bit","64 bit","128 bit","256 bit"},
            {"Internet Explorer","Mosaic","Mozilla","Nexus"},
            {"Rabbit","Creeper Virus","Elk Cloner","SCA Virus"},
            {"Security","Data Transmission","Authentication","Monitoring"},
            {"C","Java","J2EE","Prolog"}
    };

    public static String correctAnswers[] = {
            "128 bit",
            "Nexus",
            "Creeper Virus",
            "Security",
            "Prolog"

    };
}
