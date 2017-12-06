library(shiny)

shinyUI(pageWithSidebar(
  headerPanel("Розв'язання квадратних рівнянь"),
  sidebarPanel(
    
    numericInput("a", "a=", 0),
    numericInput("b", "b=", 0),
    numericInput("c", "c=", 0),
    submitButton("Розв'язати")
  ),
  mainPanel(
    
    h2("Коефіціенти рівняння"),
    h4("a"),
    verbatimTextOutput("oa"),
    h4("b"),
    verbatimTextOutput("ob"),
    h4("c"),
    verbatimTextOutput("oc"),
    
    h2("Корені рівняння"),
    verbatimTextOutput("sol"),
    
    h2("x1="),
    verbatimTextOutput("sol2"),
    
    h2("x2="),
    verbatimTextOutput("sol3")
  )
))

