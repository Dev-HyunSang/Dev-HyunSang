# Hey, I'm HyunSang 👋🏻
- **Back-End Software Engineer🧑🏻‍💻 [@TeamGRIT, Inc.](https://teamgrit.kr)**
- **Community Organizer [@GDG(Google Developers Group) Golang Korea](https://gdg.community.dev/gdg-golang-korea/)**
- **Department Information Security Engineering Major [@Soonchunhyang University](https://home.sch.ac.kr/security/index.jsp)**

> ***“If you can’t explain it simply, you don’t understand it well enough.  
만약 그것(이론)을 쉽게 설명할 수 없다면 당신은 그걸 충분히 잘 안다고 할 수
없습니다.”***  
**리처드 필립스 파인만(Richard Phillips Feynman)**

---

```go
type HyunSangInfo struct {
	Name       string
	Email      string
	Blog       string
	Company    string
	University string
	Community  string
	TechStack  map[string]string
}

func (info *HyunSangInfo) NewHyunSang() *HyunSangInfo {
	info.Name = "HyunSang Park"
	info.Email = "me@hyunsang.dev"
	info.Blog = "https://hyunsang.dev"
	info.Company = "Back-End Software Engineer @TeamGRIT, Inc."
	info.University = "Undergraduate Student @SCH Univ Dept. Information Security"
	info.Community = "Community Organizer @GDG Golang Korea"
	info.TechStack = map[string]string{
		"Language": "Golang, Rust 🦀, JavaScript(Vue.js)",
		"Database": "MySQL, MongoDB, SQLite, Redis",
		"Cloud":    "Amazon Web Services, Azure, Naver Cloud Platform",
		"CI/CD":    "GitHub Actions",
	}

	return info
}
```
