# Bondarava Natallia  
**PHOHE:** +37529 886 8986  |  **EMAIL:** tashad16a@gmail.com  
**ADDRESS:** BY, Grodno  

### DREAM
Full stack java developer  

### PROFESSIONAL SKILLS  
**Expert:** SQL  
**Advanced:** Delphi | Java | Windows | Git  
**Intermediate:** Python | VB | XML/XSL/XSLT | Android | MySQL  
**Novice:** JavaScript/HTML/CSS | Microsoft SQL Server | PostgreSQL  
**English level:** A1  

### CORE COMPETENCIES
Purposeful, industrious, responsible, stress-resistant, inquiring, friendly

### PROFESSIONAL PROFILE
*Company Names*, Grodno, BY	16.11.2015 - till now  
Programmer 

### EDUCATION HISTORY
**Higher**  
Yanka Kupala State University of Grodno Faculty of Mathematics and Informatics  
**Сourses**  
Java, Android  

### SAMPLE CODE
    override fun onCreateView(inflater: LayoutInflater, container: ViewGroup?, savedInstanceState: Bundle?): View? {
    
          var informationView = inflater.inflate(R.layout.fragment_lesson_information, container, false)
  
          lessonInformation = informationView.findViewById(R.id.lesson_information_text_view)
          lessonMentorIcon = informationView.findViewById(R.id.lesson_information_image_view)
  
          lessonThemesArray = resources.getStringArray(R.array.theme_lesson)
  
          if (savedInstanceState != null) {
              lastInfo = savedInstanceState.getString(ConstantName.INFORMATION_KEY)
              lessonInformation.setText(lastInfo)
          }
  
          return informationView
    }
