# print-numbers-by-nested-switch-
public class Switch {
    public static void main(String args[]) {
        int num = 4;
        for (int i = 0; i < num; i++) {
            switch (i) {
                case 1:
                    System.out.println("no 1");
                    break;
                case 2:
                    System.out.println("num 2");
                    break;
                case 3:
                    System.out.println("num 3");
                    int num2 = 8;
                    for(int j=4;j<num2;j++) {
                        switch (j) {
                            case 4:
                                System.out.println("num 4");
                                break;
                            case 5:
                                System.out.println("number is 5");
                                break;
                            case 6:
                                System.out.println("number is 6");
                                break;
                            default:
                                System.out.println(" no num");
                                break;
                        }
                    }
                default:
                    System.out.println(" num is grater than 6");
                    break;
            }
        }
    }
}
