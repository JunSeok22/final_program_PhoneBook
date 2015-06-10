# final_program_PhoneBook
phonebook program

public class PersonInfo {
	private String name;
	private String phone_num;
	private String birth;
	private String group;
	public PersonInfo(String name, String phone_num, String birth, String group){
		this.name = name;
		this.phone_num = phone_num;
		this.birth = birth;
		this.group = group;
		
	} //생성자
	public void showInfo(){
		System.out.println("이름 : "+name);
		System.out.println("전화번호 : "+phone_num);
		System.out.println("생일 : "+birth);
		System.out.println("그룹 : "+group);
		System.out.println("");
	}//정보 보여주기 메소드 
	
	public String get_group(){
		return group;
	}
	public String get_name(){
		return name;
	}
	public String get_phone_num(){
		return phone_num;
	}
	public String get_birth(){
		return birth;
	}
	public void set_name(String name){
		this.name = name;
	}
	public void set_phone_num(String phone_num){
		this.phone_num = phone_num;
	}
	public void set_birth(String birth){
		this.birth = birth;
	}
	public void set_group(String group){
		this.group = group;
	}
}
