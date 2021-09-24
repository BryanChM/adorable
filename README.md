package appcar;

import java.util.Scanner;

/**
 *
 * @author Bryan
 */
public class Appcar {

    /**
     * @param args the command line arguments
     */
    public static void main(String[] args) {
        // Consecionario
          int op1, op2, op3, op4, comprar, ID, ultimo;
          Scanner op=new Scanner(System.in);
          
          double pr1=0,pr2=0,pr3=0,pr4=0, pr5=0, pr6=0, pr7=0, pr8=0, total1=0,total2=0, total3=0, total4=0, total5=0, total6=0, total7=0, total8=0;
         // aqui esta nlas variables de precio
          do{
              System.out.println("Bienvenido"+  //aqui se da la bienvenida y se pide que ingrese
                      "\n1-INGRESAR "+
                      "\n2-Salir");
              op1=op.nextInt();
              switch (op1){
                  case 1 -> {
                     
                     
                          do{
                          System.out.println("BIENVENIDO "+   //Aqui se da a conocer el listado y dentro de cada uno hay diferentes opciones
                                  "\n1-Gama de Automoviles"+
                                  "\n2-Tipo de transmision"+
                                  "\n3-Color de pintura exterior"+
                                  "\n4-Color de tapiceria"+
                                  "\n5-Aros"+
                                  "\n6-Accesorios Exteriores"+
                                  "\n7-Accesorios Interiores"+
                                  "\n8-Accesorios Electricos"+
                                  "\n9-Terminar");
                          op2=op.nextInt();
                          switch (op2 ){
                              case 1 -> {
                                  do {
                                      System.out.println("SELECCIONES GAMA DE AUTOMOVIL"+ // este es la opcion de gama de automovil y sus precios
                                      "\n selecciones una Gama"+
                                      "\n1-Sedan economico--18400 "+
                                      "\n2-Sedan------------23570"+
                                      "\n3-Deportivo--------24100"+
                                      "\n4-Hibrido----------25100"+
                                      "\n5-Coupe------------19350"+
                                      "\n6-Copue Deportivo--24100"+
                                      "\n7-Compacto---------16190"+
                                      "\n8-Hatchback------------20150"+
                                      "\n9-Economico Version Rally--34700"  );
                                   
                              op3=op.nextInt();//
                              if(op3==1){  
                                 System.out.println("Ha selecionado Sedan economico");
                                 pr1=18400;
                              }else{
                                  if(op3==2){
                                 System.out.println("Ha selecionado Sedan");
                                 pr1=23570;
                                  }
                                  else{
                                      if(op3==3){
                                  System.out.println("Ha selecionado Deportivo");
                                 pr1=24100;
                                      }else{
                                    if (op3==4){
                                   System.out.println("Ha selecionado Hibrido");
                                 pr1=25100;
                                          }else{
                                        if(op3==5){
                                   System.out.println("Ha seleccionado Coupe");
                                   pr1=19350;
                                            
                                        }else{
                                            if(op3==6){
                                                 System.out.println("Ha selecionado Coupe Deportivo");
                                 pr1=24100;
                                            }else{
                                                if(op3==7){
                                                    System.out.println("Ha selecionado Compacto");
                                 pr1=16190;
                                                }else{
                                                    if(op3==7){
                                                        System.out.println("Ha selecionado Hatchback");
                                 pr1=20150;
                                                    }else{
                                                        if(op3==8){
                                                            System.out.println("Ha selecionado Economico Verion Rally");
                                 pr1=34700;
                                 
                                                        }
                                                    }
                                                }
                                            }
                                           
                                        }
                                    }
                                  }
                              
                                      }
                                  }
                              System.out.println("desea seguir agregando autos"+
                                      "\n 1-Si"+
                                      "\n 2-No");
                              comprar=op.nextInt();
                              }while(comprar!=2);
                                  total1=pr1;
                                  System.out.println("Total a pagar es"+(total8+total7+total6+total5+total4+total3+total2+total1));
                                  
                          }
                              case 2-> {
                                  do {
                                      System.out.println("SELECCIONE TRANSMISION");
               System.out.println("1-MANUAL------------ PRECIO 0.0");
               System.out.println("2-CVT---------------PRECIO 800.00");
               System.out.println("3-MANUAL CON TURBO--PRECIO  0.00");
               System.out.println("4-CVT con TURBO------PRECIO  800.00");
             
               op3=op.nextInt();
                              if(op3==1){
                                 System.out.println("Ha selecionado Sedan Manual");
                                 pr2=0.0;
                              }else{
                                  if(op3==2){
                                 System.out.println("Ha selecionado CVT");
                                 pr2=800;
                                  }
                                  else{
                                      if(op3==3){
                                  System.out.println("Ha selecionado Manual con turbo");
                                 pr2=0.0;
                                      }else{
                                    if (op3==4){
                                   System.out.println("Ha selecionado CVT con turbo");
                                 pr2=800;
                                    }
                                      }
                                  }
                              } 
                              System.out.println("desea seguir agregando transmision"+
                                      "\n 1-Si"+
                                      "\n 2-No");
                              comprar=op.nextInt();
                              }while(comprar!=2);
                                  total2=pr2;
                                  System.out.println("Total a pagar es"+(total8+total7+total6+total5+total4+total3+total2+total1)); //aqui se efectuara la suma 
                                  
                          }
                              case 3-> {
                                 
                              do{
                                  System.out.println("SELECCIONE COLOR DE PINTURA EXTERIOR");
               System.out.println("1-Cosmic------------0.0");
               System.out.println("2-Burgundy Night----0.00");
               System.out.println("3-Rallye Red--------0.00");
               System.out.println("4-Crystal Black-----0.00");
               System.out.println("5-Moderm Steel------0.00");
               System.out.println("6-Taffeta White------0.00");
               System.out.println("7-Energy Green ------0.00");
               System.out.println("8-Kona Coffee  ------0.00");
               System.out.println("9-Orange Fury------0.00");
               System.out.println("10-Helios Yellow------0.00");
               System.out.println("11-Sonic Gray ------0.00");
               System.out.println("12-Polished Metal------0.00");
               op3=op.nextInt();
              
                              if(op3==1){
                                 System.out.println("Ha selecionado Cosmic");
                                 pr3=0.0;
                              }else{
                                  if(op3==2){
                                 System.out.println("Ha selecionado Burgundy Night");
                                 pr3=0.00;
                                  }
                                  else{
                                      if(op3==3){
                                  System.out.println("Ha selecionado Rally Red");
                                 pr3=0.0;
                                      }else{
                                    if (op3==4){
                                   System.out.println("Ha selecionado Crystal Black");
                                 pr3=0.0;
                                    }else{
                                        if(op3==5){
                                            System.out.println("Ha seleccionado Modern Steel");
                                            pr3=0.0;
                                        }else{
                                     if(op3==6){
                                         System.out.println("Ha seleccionado Taffeta White");
                                            pr3=0.0;
                                     }else{
                                     if(op3==7){
                                         System.out.println("Ha seleccionado Energy Green");
                                            pr3=0.0;
                                     }else{
                                     if(op3==8){
                                         System.out.println("Ha seleccionado Kona Coffe");
                                            pr3=0.0;
                                     }else{
                                     if(op3==9){
                                         System.out.println("Ha seleccionado Orange Fury");
                                            pr3=0.0;
                                     }else{
                                     if(op3==10){
                                         System.out.println("Ha seleccionado Helios Yellow");
                                            pr3=0.0;
                                     }else{
                                         if(op3==11){
                                             System.out.println("Ha seleccionado Sonic Gray");
                                            pr3=0.0;
                                         }else{
                                             if(op3==12){
                                                 System.out.println("Ha seleccionado Polish Metal");
                                            pr3=0.0;
                                             }
                                         }
                                     }    
                                     }    
                                     }    
                                     }    
                                     }       
                                        }
                                    }
                                      }
                                  }
                              } 
                              System.out.println("desea seguir agregando color"+
                                      "\n 1-Si"+
                                      "\n 2-No");
                              comprar=op.nextInt();
                              }while (comprar!=2);
                              total3=pr3;
                                  System.out.println("Total a pagar es"+(total8+total7+total6+total5+total4+total3+total2+total1));
                                  break;
                              
                              
                          }case 4-> {
                                  
                              do{
                                  System.out.println("SELECCIONE Color Tapiceria");
               System.out.println("1-Gray cloth------------ PRECIO 0.0");
               System.out.println("2-Black Cloth-----------PRECIO 000.00");
               System.out.println("3-Black/Gray Cloth------PRECIO  0.00");
               System.out.println("4-Red/Black Suede------PRECIO  0.00");
             
               op3=op.nextInt();
                              if(op3==1){
                                 System.out.println("Ha selecionado Gray cloth");
                                 pr4=0.0;
                              }else{
                                  if(op3==2){
                                 System.out.println("Ha selecionado Black Cloth");
                                 pr4=0.0;
                                  }
                                  else{
                                      if(op3==3){
                                  System.out.println("Ha selecionado Black/Gray Clotho");
                                 pr4=0.0;
                                      }else{
                                    if (op3==4){
                                   System.out.println("Ha selecionado Red/Black Suede");
                                 pr4=0.0;
                                    }
                                      }
                                  }
                              } 
                              System.out.println("desea seguir agregando Tapiceria"+
                                      "\n 1-Si"+
                                      "\n 2-No");
                               comprar=op.nextInt();
                              }while (comprar!=2);
                              total4=pr4;
                                  System.out.println("Total a pagar es"+(total8+total7+total6+total5+total4+total3+total2+total1));
                                  break;
                          }case 5-> {
                              do{
                                   System.out.println("SELECCIONE AROS");
               System.out.println("1-15------------ PRECIO 0.0");
               System.out.println("2-16---------- PRECIO 0.00");
               System.out.println("3-17   ------PRECIO  1688");
               System.out.println("4-18------PRECIO  1700");
                System.out.println("5-18------PRECIO 3011 ");
             
               op3=op.nextInt();
                              if(op3==1){
                                 System.out.println("Ha selecionado aros de 15");
                                 pr5=0.0;
                              }else{
                                  if(op3==2){
                                 System.out.println("Ha selecionado aros de 16");
                                 pr5=0.0;
                                  }
                                  else{
                                      if(op3==3){
                                  System.out.println("Ha selecionado aros de 17");
                                 pr5=1688;
                                      }else{
                                    if (op3==4){
                                   System.out.println("Ha selecionado aros de 18");
                                 pr5=1700;
                                    }else{
                                        if(op3==5){
                                            System.out.println("Ha seleccioando aros de 19");
                                            pr5=3011;
                                        }
                                    }
                                      }
                                  }
                              } 
                              System.out.println("desea seguir agregando AROS"+
                                      "\n 1-Si"+
                                      "\n 2-No");
                               comprar=op.nextInt();
                            
                              }while (comprar!=2);
                              total5=pr5;
                                  System.out.println("Total a pagar es"+(total8+total7+total6+total5+total4+total3+total2+total1));
                                  break;
                          } case 6 -> {
                              do{
                                  System.out.println("SELECCIONE COLOR DE PINTURA EXTERIOR");
               System.out.println("1-Body Side Molding --- 217");
               System.out.println("2-Car Cover-------------230");
               System.out.println("3-Decklid Spoller--- ---299");
               System.out.println("4-Door Edge Film--------42");
               System.out.println("5-Door Edge Guards------84");
               System.out.println("6-Door Trim Chrome------285");
               System.out.println("7-Door Visor ------185");
               System.out.println("8-Front Fender Embiems -----50");
               System.out.println("9-Rear Bumper Applique------70");
               System.out.println("10-Fog Lights   -----325");
               System.out.println("11-Nose Mascs ------158");
               System.out.println("12-Moonrof Visor------138");
                 System.out.println("13-Splash Guard Set---104");
                 System.out.println("14-Dust Cover---------350");
                   System.out.println("15-Door Mirror Cover-Carbon fiber--520");
               op3=op.nextInt();
              
                              if(op3==1){
                                 System.out.println("Ha selecionado Body Side Molding");
                                 pr6=217;
                              }else{
                                  if(op3==2){
                                 System.out.println("Ha selecionado Car Cover");
                                 pr6=230;
                                  }
                                  else{
                                      if(op3==3){
                                  System.out.println("Ha selecionado Decklid Spoiler");
                                 pr6=299;
                                      }else{
                                    if (op3==4){
                                   System.out.println("Ha selecionado Door Edge Film");
                                 pr6=42;
                                    }else{
                                        if(op3==5){
                                            System.out.println("Ha seleccionado Door Edge Guards");
                                            pr6=84;
                                        }else{
                                     if(op3==6){
                                         System.out.println("Ha seleccionado Door Trim Chromee");
                                            pr6=285;
                                     }else{
                                     if(op3==7){
                                         System.out.println("Ha seleccionado Door Visor");
                                            pr6=185;
                                     }else{
                                     if(op3==8){
                                         System.out.println("Ha seleccionado Front Fender Emblems");
                                            pr6=50;
                                     }else{
                                     if(op3==9){
                                         System.out.println("Ha seleccionado Rear Bumper Applique");
                                            pr6=70;
                                     }else{
                                     if(op3==10){
                                         System.out.println("Ha seleccionado Fog Lights");
                                            pr6=325;
                                     }else{
                                         if(op3==11){
                                             System.out.println("Ha seleccionado Nose Mascs");
                                            pr6=158;
                                         }else{
                                             if(op3==12){
                                                 System.out.println("Ha seleccionado Moonrof Visor");
                                            pr6=138;
                                             }else{
                                                 if(op3==13){
                                                     System.out.println("Ha seleccionado Splash Guard Set");
                                                     pr6=104;
                                                 }else{
                                                     if(op3==14){
                                                         System.out.println("Ha seleccioando Dust cover");
                                                         pr6=350;
                                                         
                                                     }else{
                                                         if(op3==15){
                                                             System.out.println("Ha seleccionado Door Mirro Cover- Carbon Fiber");
                                                             pr6=520;
                                                         }
                                                     }
                                                 }
                                             }
                                         }
                                     }    
                                     }    
                                     }    
                                     }    
                                     }       
                                        }
                                    }
                                      }
                                  }
                              }
                              System.out.println("desea seguir agregando Pintura Exterior"+
                                      "\n 1-Si"+
                                      "\n 2-No");
                               comprar=op.nextInt();
                              }while (comprar!=2);
                              total6=pr5;
                                  System.out.println("Total a pagar es"+(total8+total7+total6+total5+total4+total3+total2+total1));
                                  break;
                          } case 7->{
                              do {
                                  System.out.println("SELECCIONE ACCESORIOS INTERIORES");
               System.out.println("1-All-Season Floor Matas----142");
               System.out.println("2-Automatic-Dimming Mirror--219");
               System.out.println("3-Cargo Hook----------------12");
               System.out.println("4-Cargo Net-----------------49");
               System.out.println("5-Console Illumination-------250");
               System.out.println("6-Cargo Organizer------------87");
               System.out.println("7-Door Paner Protector-------149");
               System.out.println("8-Armrest Compartiment-------337");
               System.out.println("9-Door Sill Trim-Illluminated-290");
               System.out.println("10-Cargo Cover---------------166");
               System.out.println("11-Cargo Liner---------------187");
               op3=op.nextInt();
              
                              if(op3==1){
                                 System.out.println("Ha selecionado All-Seasons Floor Mats");
                                 pr3=0.0;
                              }else{
                                  if(op3==2){
                                 System.out.println("Ha selecionado Automatic-Dimming Mirror");
                                 pr3=0.00;
                                  }
                                  else{
                                      if(op3==3){
                                  System.out.println("Ha selecionado Cargo Hook");
                                 pr3=0.0;
                                      }else{
                                    if (op3==4){
                                   System.out.println("Ha selecionado Cargo Net");
                                 pr3=0.0;
                                    }else{
                                        if(op3==5){
                                            System.out.println("Ha seleccionado Console Illumination");
                                            pr3=0.0;
                                        }else{
                                     if(op3==6){
                                         System.out.println("Ha seleccionado Cargo Organizer");
                                            pr3=0.0;
                                     }else{
                                     if(op3==7){
                                         System.out.println("Ha seleccionado Door Panel Protector");
                                            pr3=0.0;
                                     }else{
                                     if(op3==8){
                                         System.out.println("Ha seleccionado Armrest Compartiment");
                                            pr3=0.0;
                                     }else{
                                     if(op3==9){
                                         System.out.println("Ha seleccionado Door Sill Trim-Illuminated");
                                            pr3=0.0;
                                     }else{
                                     if(op3==10){
                                         System.out.println("Ha seleccionado Cargo Cover");
                                            pr3=0.0;
                                     }else{
                                         if(op3==11){
                                             System.out.println("Ha seleccionado Cargo Liner");
                                            pr3=0.0;
                                         }
                                         }
                                     }    
                                     }    
                                     }    
                                     }    
                                     }       
                                        }
                                    }
                                      }
                                  }
                              System.out.println("desea seguir agregando accesorios Interiores"+
                                      "\n 1-Si"+
                                      "\n 2-No");
                               comprar=op.nextInt();
                              } while(comprar!=2);
                                      total7=pr7;
                                  System.out.println("Total a pagar es"+(total8+total7+total6+total5+total4+total3+total2+total1));
                                  break;
                                      
                                  
                              } case 8->{
                                  do {
                                       System.out.println("SELECCIONE Accesorios Electronicos");
               System.out.println("1-Wirelless Phone Charge---305");
               System.out.println("2-USB Charger-2.1 Amp.-----120");
               System.out.println("3-Puddle Light-------------185");
               System.out.println("4-Parking Sensores---------514");
                
               op3=op.nextInt();
                              if(op3==1){
                                 System.out.println("Ha selecionado Wireless Phone Charger");
                                 pr8=305;
                              }else{
                                  if(op3==2){
                                 System.out.println("Ha selecionado USB Charger - 2.1 Amp.");
                                 pr8=120;
                                  }
                                  else{
                                      if(op3==3){
                                  System.out.println("Ha selecionado Puddle Light");
                                 pr8=185;
                                      }else{
                                    if (op3==4){
                                   System.out.println("Ha selecionado Parking Sensors");
                                 pr8=514;
                                    }
                                      }
                                  }
                              }  
                              System.out.println("desea seguir agregando accesoriios Elecctronicos"+
                                      "\n 1-Si"+
                                      "\n 2-No");
                               comprar=op.nextInt();
                                      
                                  }while(comprar!=2);
                                      total8=pr8;
                                  System.out.println("Total a pagar es"+"\n"+(total8+total7+total6+total5+total4+total3+total2+total1));
                                  break;
                              }case 9-> {
                                  System.out.println("Gracias por la compra"+
                                          "\n Total a Pagar es"+(total8+total7+total6+total5+total4+total3+total2+total1));
                              break;
                              }
                              
                          }
                                  
                              
                                  
                      }
                         while(op2!=9);
                      
                  }
                  case 2 -> {
                      System.out.println("Gracias por haber Utilizado el Sistema");
                  }
              }
            
          }while (op1!=2);
    }
    
}
