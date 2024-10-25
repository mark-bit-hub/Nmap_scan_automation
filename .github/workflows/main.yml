#include <iostream>
#include <string>

using namespace std;

int main() {
    string target_ip;
    string command;
    int choice;

    while (true) {
        cout << "Choose an action:\n";
        cout << "1. List scan\n";
        cout << "2. TCP connect scan\n";
        cout << "3. Ping scan\n";
        cout << "4. Stealth scan\n";
        cout << "5. Null scan\n";
        cout << "6. FIN scan\n";
        cout << "7. Xmas scan\n";
        cout << "8. UDP scan\n";
        cout << "9. Version detection\n";
        cout << "10. OS detection\n";
        cout << "11. Aggressive scan\n";
        cout << "12. Exit\n";

        cin >> choice;

        switch (choice) {
            case 1:
                cout << "Enter the target IP address: ";
                cin >> target_ip;
                command = "nmap -sL " + target_ip;
                break;
            case 2:
                cout << "Enter the target IP address: ";
                cin >> target_ip;
                command = "nmap -sT " + target_ip;
                break;
            case 3:
                cout << "Enter the target IP address: ";
                cin >> target_ip;
                command = "nmap -sP " + target_ip;
                break;
            case 4:
                cout << "Enter the target IP address: ";
                cin >> target_ip;
                command = "nmap -sS " + target_ip;
                break;
            case 5:
                cout << "Enter the target IP address: ";
                cin >> target_ip;
                command = "nmap -sN " + target_ip;
                break;
            case 6:
                cout << "Enter the target IP address: ";
                cin >> target_ip;
                command = "nmap -sF " + target_ip;
                break;
            case 7:
                cout << "Enter the target IP address: ";
                cin >> target_ip;
                command = "nmap -sX " + target_ip;
                break;
            case 8:
                cout << "Enter the target IP address: ";
                cin >> target_ip;
                command = "nmap -sU " + target_ip;
                break;
            case 9:
                cout << "Enter the target IP address: ";
                cin >> target_ip;
                command = "nmap -sV " + target_ip;
                break;
            case 10:
                cout << "Enter the target IP address: ";
                cin >> target_ip;
                command = "nmap -O " + target_ip;
                break;
            case 11:
                cout << "Enter the target IP address: ";
                cin >> target_ip;
                command = "nmap -A " + target_ip;
                break;
            case 12:
                exit(0);
            default:
                cout << "Invalid choice.\n";
                continue;
        }

        system(command.c_str());
    }

    return 0;
}
