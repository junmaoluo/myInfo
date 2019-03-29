# myInfo
myinfomation
class Hunter{
	private String name = "Keith";
	private String phoneNumber = "18620720795";
	private String brief = "我是一个会编程的猎头，欢迎来骚扰";
	
	private Candidate can;
	
	public Hunter() {
		
	}
	
	public Hunter(String name, String phoneNumber, String brief) {
		super();
		this.name = name;
		this.phoneNumber = phoneNumber;
		this.brief = brief;
	}
	
	
	public String getName() {
		return name;
	}
	public void setName(String name) {
		this.name = name;
	}
	public String getPhoneNumber() {
		return phoneNumber;
	}
	public void setPhoneNumber(String phoneNumber) {
		this.phoneNumber = phoneNumber;
	}
	public String getBrief() {
		return brief;
	}
	public void setBrief(String brief) {
		this.brief = brief;
	}
	public Candidate getCan() {
		return can;
	}

	public void setCan(Candidate can) {
		this.can = can;
	}

	public void feedBack() {
		System.out.println("谢谢你的信任，" + can.getName() + "。");
		System.out.println("我已经收到你的简历，我会帮你推荐相关的职位的。");
	}
}
