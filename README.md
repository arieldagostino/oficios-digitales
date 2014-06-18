oficios-digitales
==============*Error al ingresar dos números de igual valor
*Se ingresan dos números iguales para que se efectué el error.
*Resultado:
Ingrese tres numeros diferentes 1
2
1
El menor es = null
Error en la actividad 9 ej. 2 #2
*Código del programa:
def minimo(num1,num2,num3){
def resultado
if ((num1<num2) && (num1<num3)){
resultado=num1

}
if ((num2<num3) && (num2<num1)){
resultado=num2
}
if ((num3<num2) && (num3<num1)){
resultado=num3
}
return resultado
}

def numero1=System.console().readLine("Ingrese tres numeros diferentes ").toInteger()
def numero2=System.console().readLine().toInteger()
def numero3=System.console().readLine().toInteger()
def res

res=minimo(numero1,numero2,numero3)
println "El menor es = " + res




En el ejercicio de la estructura while de la pagina 27 "sumatoria" al ingresar un caracter en lugar de un numero devuelve un error:

org.codehaus.groovy.control.MultipleCompilationErrorsException: startup failed:
/home/gEkIUF/prog.groovy: 2: expecting anything but ''\n''; got it anyway @ line 2, column 25.
def numero_ingresado = "
^

1 error
