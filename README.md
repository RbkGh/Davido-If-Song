##Davido - If song rendered in different languages for fun with inspiration from [@threefacedcoin's](https://twitter.com/threefacedcoin) tweet [here](https://twitter.com/threefacedcoin/status/872365153358151681) just for fun


##Sample Stanza 1 - Java Version
```
public class DavidoIf {

    public static void main(String[] args) throws InterruptedException {
        Body myBody = new MyBody();
        Body yourBody = new YourBody();
        myBody.equals(null);
        Thread.sleep(3000); //wait three seconds after intro
        if (I.tellYouSay("I").LoveYou) {
            Thread.sleep(2000);
            myBody.equals(yourBody);
            I.accountBalance(30000000000.00);
            yourBody.versaceAndGucci();
        }
        noDo();
        gararaForMe();
        noDo();
        senrereO();
        noDo();
        shakaraOwe();
    }
    /**
     * repeat 'no do' 3X,considering 2 second break on second 'no do'
     */
    private static void noDo() throws InterruptedException {
        int[] chorusLoop = {1,2,3};
        for (int i : chorusLoop){
            System.out.println("No Do");
            if(i==2){
                Thread.sleep(2000);
            }
        }
    }
    private static void gararaForMe(){
        System.out.println("Garara For Me");
    }
    private static void senrereO(){
        System.out.println("Senrere oo");
    }
    private static void shakaraOwe(){
        System.out.println("Shakara Owe");
    }
    public static class I {
        private boolean LoveYou =true;
        public static final String LOVE_YOU="Love You O,";
        private static I iInstance = new I();
        private static void accountBalance(double accountBalance ){
            System.out.println(accountBalance+" for the account oo");
        }
        private I() {
            System.out.println("If I tell you say");
        }
        public static I tellYouSay(String statement) {
            System.out.println(statement+" "+LOVE_YOU);
            return iInstance;
        }
    }
    public interface Body{
          default boolean versaceAndGucci(){
              return true;
          }
          default void equals(Body body){
              String moneyPlusBodyNaYourOwn="My money my body na your own ";
              if(Objects.isNull(body))
              System.out.println(moneyPlusBodyNaYourOwn);
              else
                  System.out.println(moneyPlusBodyNaYourOwn+" o baby");
          }
    }
    public static class MyBody implements Body{}
    public static class YourBody implements Body{}
}
```

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Added some feature/added js version'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request