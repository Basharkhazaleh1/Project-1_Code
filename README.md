class System 
{ 
    private char Name;
    private ReportComment com;
    private  static ArrayList<Book> B1 = new ArrayList<Book>();
    public void setName(){};
    public char getName(){return Name;}
    public void Register(){}
    public void Login(){}
    public void Search(){}
    public void LogOut(){}
    public ReportComment ReportCom(ReportComment C){return C;}
    public void Subscribe(){}

}
class Admin 
{
    private String Name;
    private String Password;
    private String Email;
    private int ID;
    private  static ArrayList<ReportComment> R1 = new ArrayList<ReportComment>();
    public void setName(){};
    public String getName(){return Name;}
    public void setPassword(){};
    public String getPassword(){return Password;}
    public void setEmail(){};
    public String getEmail(){return Email;}
    public void setID(){};
    public int getID(){return ID;}
    public void BlockUser(){}
    public void Delete(){}
    public ArrayList<ReportComment> getReport(){return R1;} 
}
class Book 
{
    private String Name;
    private String Author;
    private String BookType;
    private int ISBN;
    public void setName(){};
    public String getName(){return Name;}
    public void setAuthor(){};
    public String getAuthor(){return Author;}
    public void setBookType(){};
    public String getBookType(){return BookType;}
    public void setISBN(){};
    public int getISBN(){return ISBN;}
    public void comment(){}
}
class Free 
{
    public void AllBook(){}
    public void Download(){}
}
class Buy 
{
    public void BuyBook(){}
    public void Download(){}
}
class ReportComment 
{
    private  static ArrayList<Account> A1 = new ArrayList<Account>();
    private  SearchComment loc;
    public String getSub(){return " ";}
    public String getFree(){return " " ;}
    public String getReport(){return " ";}
    public void ReportComment(String loc){}
}
class SearchComment 
{
    private String Location;
    public void setLoc(){}
    public String getloc(){return Location;}
}
class Account 
{
    private String Name;
    private String Password;
    private String Email;
    private int ID;
     public void setName(){};
    public String getName(){return Name;}
    public void setPassword(){};
    public String getPassword(){return Password;}
    public void setEmail(){};
    public String getEmail(){return Email;}
    public void setID(){};
    public int getID(){return ID;}
}
class SubscribeUser 
{
    private Data Time;
    public Data getEndTime(){return Time;}
}
