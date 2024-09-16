# best-repo-ever
public class Accountdelete {
    public void accdel(){
        list<account> acc = [select id,name from account where name = 'Dickenson'];           
        delete acc;
    }
}
