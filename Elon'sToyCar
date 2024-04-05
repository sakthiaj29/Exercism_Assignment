public class ElonsToyCar {
    int count=0;
    public static ElonsToyCar buy() {
        return new ElonsToyCar();
    }

    public String distanceDisplay() {
        return "Driven " +count*20+" meters";
    }

    public String batteryDisplay() {
        if(count>=100){
            distanceDisplay();
            return "Battery empty";
            
        }
        return "Battery at "+(100-count)+"%";
    }

    public void drive() {
        if(count<100){
             count++;   
        }
    }
}
