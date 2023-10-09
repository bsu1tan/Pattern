
public class Server extends Computer {
    // Define a class named 'Server' that extends the 'Computer' class
// Определение класса 'Server', который расширяет класс 'Computer'

    // Declare private instance variables to store information about the server
    // Объявление приватных переменных экземпляра для хранения информации о сервере
    private String ram;// RAM (Random Access Memory) of the server / Оперативная память (RAM) сервера
    private String hdd;// HDD (Hard Disk Drive) of the server / Жесткий диск (HDD) сервера
    private String cpu;// CPU (Central Processing Unit) of the server / Центральный процессор (CPU) сервера



    // Constructor for the 'Server' class that takes RAM, HDD, and CPU as parameters
    // Конструктор класса 'Server', принимающий RAM, HDD и CPU в качестве параметров
    public Server(String ram, String hdd, String cpu){
        this.ram=ram;// Initialize the 'ram' instance variable with the provided value
        // / Инициализация переменной экземпляра 'ram' предоставленным значением
        this.hdd=hdd;  // Initialize the 'hdd' instance variable with the provided value
        // / Инициализация переменной экземпляра 'hdd' предоставленным значением

        this.cpu=cpu;// Initialize the 'cpu' instance variable with the provided value
        // / Инициализация переменной экземпляра 'cpu' предоставленным значением
    }

    // Override the 'getRAM' method from the 'Computer' class
    // Переопределение метода 'getRAM' из класса 'Computer'
    @Override
    public String getRAM() {
        return this.ram;// Return the RAM of the server / Возвращение RAM сервера
    }

    // Override the 'getHDD' method from the 'Computer' class
    // Переопределение метода 'getHDD' из класса 'Computer'
    @Override
    public String getHDD() {
        return this.hdd;// Return the HDD of the server / Возвращение HDD сервера
    }

    // Override the 'getCPU' method from the 'Computer' class
    // Переопределение метода 'getCPU' из класса 'Computer'
    @Override
    public String getCPU() {
        return this.cpu;// Return the CPU of the server / Возвращение CPU сервера
    }
}
