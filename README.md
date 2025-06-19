##  Inventory Management System

class Product {
    int productId;
    String productName;
    int quantity;
    double price;

    Product(int productId, String productName, int quantity, double price) {
        this.productId = productId;
        this.productName = productName;
        this.quantity = quantity;
        this.price = price;
    }
}

import java.util.*;

class Inventory {
    Map<Integer, Product> inventory = new HashMap<>();

    void addProduct(Product p) {
        inventory.put(p.productId, p);
    }

    void updateProduct(Product p) {
        inventory.put(p.productId, p);
    }

    void deleteProduct(int productId) {
        inventory.remove(productId);
    }
}
# Digital-Nurture-4.O---Vinith
