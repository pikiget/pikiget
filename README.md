<h1 align="center">
  
</h1>

¡Hola! Soy Roy, un estudiante que actualmente vive en Lima, Perú. Me estoy preparando para 
ser programador full stack a través de pequeños proyectos. 
<br>

<p>
<div align="center">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=E34F26&labelColor=282828">
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=1572B6&labelColor=282828">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=F7DF1E&labelColor=282828">
  <img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=61DAFB&labelColor=282828">
  <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=ED8B00&labelColor=282828">
  

  
</div>
</p>

```Java
public class Roy8a {
  private String nombre;
  private String usuario;
  private String ubicacion;
  private String instagram;

  //Constructor :v
  public Roy8a(String nombre, String usuario, String ubicacion, String instagram){
    this.nombre = nombre;
    this.usuario = usuario;
    this.ubicacion = ubicacion;
    this.instagram = instagram;
  }
  @Override
  public String toString() {
    return "**Información del Usuario:**\n" +
           "Nombre: " + nombre + "\n" +
           "Usuario: " + usuario + "\n" +
           "Ubicación: " + ubicacion + "\n" +
           "Instagram: " + instagram;
  }

  public static void main(String[] args) {
    Roy8a yo = new Roy8a("Roy Ochoa", "pikiget", "Lima, Perú", "roy8.a");
    System.out.println(yo);
  }
}
```

