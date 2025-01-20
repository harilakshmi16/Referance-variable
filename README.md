# Referance-variable
Reference Variable

class ReferenceExample {
    int value;

    public void setValue(int value) {
        this.value = value;
    }

    public void display() {
        System.out.println("Value: " + value);
    }
}

public class ReferenceVariable {
    public static void main(String[] args) {
        ReferenceExample ref = new ReferenceExample();
        ref.setValue(42);
        ref.display();
    }
}

Output

Value: 42
