# COLLECTION-FRAMEWORK-DATE-AND-TIME-CLASSpackage collection.framework.date.and.time.clas;
import java.util.Date;
import java.util.Calendar;
import java.util.Scanner;
/**
 *
 * @author 1BSCCSA44
 */
public class CollectionFrameworkDateAndTimeClas {

    /**
     * @param args the command line arguments
     */
    public static void main(String[] args) {
        Calendar calendar = Calendar.getInstance();
        System.out.println("Current Date and Time:" + calendar.getTime());
        Scanner scanner = new Scanner(System.in);
System.out.print("Enter the number of days to add:");
int daysToAdd = scanner.nextInt();
Date updatedDate = calendar.getTime();
System.out.println("Updated Date:" + updatedDate);
scanner.close();
        // TODO code application logic here
    }
    
}

OUTPUT
Current Date and Time:Tue Feb 25 17:11:09 IST 2025
Enter the number of days to add:24
Updated Date:Tue Feb 25 17:11:09 IST 2025
BUILD SUCCESSFUL (total time: 9 seconds)
