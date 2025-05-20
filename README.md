# 📄 Documentación del Proyecto: Sistema de Facturación en C#

**Nombre:** Ángel Yandell
**Apellido:** Cuevas Mora
**Curso:** 5to B Informática
**Materia:** Desarrollo de Aplicaciones Informáticas
**Tema:** Documentación Creación de Reportes
**Docente:** Víctor Recio

---

## 🛠️ PASO 1: Crear el archivo `README.md` en Visual Studio 2022

1.  Abre tu proyecto en **Visual Studio 2022**.
2.  Haz clic derecho en el nombre del proyecto (`SistemaFacturacion`) dentro del **Explorador de soluciones**.
    ![imagen1]([imagen1.png](https://private-user-images.githubusercontent.com/151237648/445654556-bd0540c6-a0dd-4ac2-9b58-70d30f88a238.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3NDc3NTE2MDEsIm5iZiI6MTc0Nzc1MTMwMSwicGF0aCI6Ii8xNTEyMzc2NDgvNDQ1NjU0NTU2LWJkMDU0MGM2LWEwZGQtNGFjMi05YjU4LTcwZDMwZjg4YTIzOC5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjUwNTIwJTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI1MDUyMFQxNDI4MjFaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT1jYzFmMWE3M2MyMThhNjc0YmYxYTViM2UyZWQ2MWVkNDE5ODk4MDRkM2EzZmFmMDJlMDk0YTVjODEyYWZlYTViJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCJ9.H0_6f6zS6nQDGigDwSJDA7ysjXKSAUvHn4IfSyfFA7o))
    Selecciona **Agregar > Nuevo elemento...**.
    ![imagen2]([imagen2.png](https://private-user-images.githubusercontent.com/151237648/445654560-ea4a99fe-5783-45f3-96a6-b65484c1396d.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3NDc3NTE2MDEsIm5iZiI6MTc0Nzc1MTMwMSwicGF0aCI6Ii8xNTEyMzc2NDgvNDQ1NjU0NTYwLWVhNGE5OWZlLTU3ODMtNDVmMy05NmE2LWI2NTQ4NGMxMzk2ZC5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjUwNTIwJTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI1MDUyMFQxNDI4MjFaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT1kMDA0YzVkZDIzMTIxZmEyMjA2ZWVjYTc0ZTAyYWE1MDEyZjBjM2Y0ZjRmMWFhYzk2MDE2MzIzNzMxY2MxMzlhJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCJ9.PUIIp-b8MzIssMxxsuDBwU6NjozkM309PLeTx9pwqq0))
4.  En la búsqueda escribe: `Archivo de texto`
    ![imagen3]([imagen3.png](https://private-user-images.githubusercontent.com/151237648/445654561-ba83a978-55d8-4a17-8e06-1cdc8aae4f89.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3NDc3NTE2MDEsIm5iZiI6MTc0Nzc1MTMwMSwicGF0aCI6Ii8xNTEyMzc2NDgvNDQ1NjU0NTYxLWJhODNhOTc4LTU1ZDgtNGExNy04ZTA2LTFjZGM4YWFlNGY4OS5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjUwNTIwJTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI1MDUyMFQxNDI4MjFaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT01NDdhNjUzNmEzNjMyZWE4YTI4ZGQxZWFkYzllYzMxN2ZmM2I2NDNhZTJhZDg5NzlmNTJmYzBiMDM4MjdmMDdmJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCJ9.yWKjoE_BiAVcT2cD60g69uR7nxc3ZdB4OqZ4oWiZ7ws))
5.  Cámbiale el nombre a exactamente: `README.md`.
6.  Haz clic en **Agregar**.

---

## 👓 PASO 2: Instalar extensión para Markdown (opcional)

Si quieres ver una vista previa de cómo se ve el archivo `.md` dentro de Visual Studio:

1.  Ve al menú superior y selecciona: **Extensiones > Administrar extensiones**.

 
 ![imagen4]([imagen4.png](https://private-user-images.githubusercontent.com/151237648/445654553-15227a20-2ffa-4a99-8721-95db275a39b2.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3NDc3NTE4NjksIm5iZiI6MTc0Nzc1MTU2OSwicGF0aCI6Ii8xNTEyMzc2NDgvNDQ1NjU0NTUzLTE1MjI3YTIwLTJmZmEtNGE5OS04NzIxLTk1ZGIyNzVhMzliMi5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjUwNTIwJTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI1MDUyMFQxNDMyNDlaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT0xZjBiNmRjNDY1OGRkNDdkYjcxM2U1YjgxNjJmNDViZDY0ZmUzMmFjNTY2YWNhZGY5ZGZiNzBhYWRhZWJmNTUxJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCJ9.dClFT2GF30mboKgxrrYjGAbqQ3_aw2SAM6M1cw3hNr4))

2.  En la barra de búsqueda escribe: `Markdown Editor`.
![imagen5]([imagen5.png](https://private-user-images.githubusercontent.com/151237648/445654557-d4f95257-d996-4767-b48f-82f16dbca242.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3NDc3NTE4NjksIm5iZiI6MTc0Nzc1MTU2OSwicGF0aCI6Ii8xNTEyMzc2NDgvNDQ1NjU0NTU3LWQ0Zjk1MjU3LWQ5OTYtNDc2Ny1iNDhmLTgyZjE2ZGJjYTI0Mi5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjUwNTIwJTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI1MDUyMFQxNDMyNDlaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT1mYjlhYWVlZWUwMzE4YmI5NGRkYTMyMWJlYTQ2YjAwMzVkOTdiYzMxOWEzM2I1ZmY1ZGRiYmE5Yjk3MzNjYmJjJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCJ9.WeIJZnrV9kM3B6oTzyPfps-ylWnYzJiX459IKnrpIQY))

3.  Selecciona el resultado y haz clic en **Descargar**.


4.  Reinicia Visual Studio para que se aplique la instalación.

---

## ✍️ PASO 3: Escribir la documentación dentro del archivo `README.md`

A continuación, se recomienda una estructura para documentar tu sistema de facturación:

---

# 🧾 Sistema de Facturación en C#

Este sistema fue desarrollado con **Windows Forms en C#**, utilizando **SQL Server**, **Entity Framework** y **ReportViewer** para la creación de reportes de facturas.

---

## 📁 Estructura del Proyecto

SistemaFacturacion/
│
├── Models/
│   ├── Categoria.cs
│   ├── FacturaDetalle.cs
│   └── FacturaContext.cs
│
├── InsertarFactura.cs
├── VerFacturas.cs
├── ReporteFactura.cs
├── FacturaReporte.rdlc
└── README.md


---

## 📦 Requisitos

-   Visual Studio 2022
-   .NET Framework 4.8
-   SQL Server (nombre del servidor: **AYC**, con autenticación de Windows)
-   Paquete NuGet: `Microsoft.Reporting.WinForms`
-   Entity Framework 6
-   ReportViewer

---

## 🧱 Estructura de la base de datos

Nombre de la base de datos: **BD_FacturacionPruebas**

```sql
CREATE TABLE Categorias (
    Id INT PRIMARY KEY IDENTITY(1,1),
    Nombre VARCHAR(50) NOT NULL
);

CREATE TABLE FacturaDetalle (
    ID INT PRIMARY KEY IDENTITY(1,1),
    Descripcion VARCHAR(100),
    Categoria VARCHAR(50),
    Cantidad INT,
    PrecioUnitario DECIMAL(10,2),
    Itebis DECIMAL(10,2),
    Descuento DECIMAL(10,2),
    TotalGeneral DECIMAL(10,2)
);

INSERT INTO Categorias (Nombre) VALUES
('Cereales'), ('Lácteos'), ('Carnes'), ('Verduras'), ('Frutas'),
('Bebidas'), ('Snacks'), ('Limpieza'), ('Higiene personal'),
('Panadería'), ('Otros');

``` 

## 🧠 ¿Qué hace el sistema?

Permite insertar nuevas facturas.
Muestra todas las facturas registradas.
Permite editar o eliminar facturas.
Genera reportes con ReportViewer.
Calcula automáticamente el total general con ITEBIS y descuento.

## 🧩 Formularios principales

## InsertarFactura.cs
Formulario para ingresar o editar facturas. Incluye validación, cálculo automático y conexión a la base de datos.

## Controles principales:

#### txtDesc: TextBox para descripción
#### cbCategoria: ComboBox con categorías desde SQL
#### numCantidad: NumericUpDown
#### txtPrecio, txtItebis, txtDescuento: TextBox
#### btnGuardar, btnVerRegistroDeFacturas, btnCerrar: Botones

```C#
using System;
using System.Linq;
using System.Windows.Forms;
using SistemaFacturacion.Models;
using SistemaFacturacion;

namespace SistemaFacturacionCSharp
{
    public partial class InsertarFactura : Form
    {
        private readonly FacturaContext db = new FacturaContext();
        private int? facturaId = null;

        public InsertarFactura()
        {
            InitializeComponent();
            CargarCategorias();
        }

        public InsertarFactura(int id) : this()
        {
            facturaId = id;
            CargarFacturaExistente();
        }

        private void CargarCategorias()
        {
            var categorias = db.Categorias.ToList();

            categorias.Insert(0, new Categoria { Nombre = "Seleccione una categoría" });

            cbCategoria.DataSource = categorias;
            cbCategoria.DisplayMember = "Nombre";
            cbCategoria.ValueMember = "Nombre";
            cbCategoria.SelectedIndex = 0;
        }

        private void CargarFacturaExistente()
        {
            var factura = db.FacturaDetalle.Find(facturaId);
            if (factura != null)
            {
                txtDesc.Text = factura.Descripcion;
                cbCategoria.SelectedValue = factura.Categoria;
                numCantidad.Value = factura.Cantidad;
                txtPrecio.Text = factura.PrecioUnitario.ToString("0.00");
                txtItebis.Text = factura.Itebis.ToString("0.00");
                txtDescuento.Text = factura.Descuento.ToString("0.00");
            }
        }

        private void btnGuardar_Click(object sender, EventArgs e)
        {
            if (string.IsNullOrWhiteSpace(txtDesc.Text))
            {
                MessageBox.Show("Ingrese la descripción.");
                return;
            }

            if (cbCategoria.SelectedIndex == 0)
            {
                MessageBox.Show("Debe seleccionar una categoría válida.");
                return;
            }

            FacturaDetalle factura;

            if (facturaId.HasValue)
            {
                factura = db.FacturaDetalle.Find(facturaId.Value);
                if (factura == null)
                {
                    MessageBox.Show("Factura no encontrada.");
                    return;
                }
            }
            else
            {
                factura = new FacturaDetalle();
                db.FacturaDetalle.Add(factura);
            }

            factura.Descripcion = txtDesc.Text.Trim();
            factura.Categoria = cbCategoria.SelectedValue.ToString();
            factura.Cantidad = (int)numCantidad.Value;
            factura.PrecioUnitario = decimal.Parse(txtPrecio.Text);
            factura.Itebis = decimal.Parse(txtItebis.Text);
            factura.Descuento = decimal.Parse(txtDescuento.Text);
            factura.TotalGeneral = (factura.Cantidad * factura.PrecioUnitario) + factura.Itebis - factura.Descuento;

            db.SaveChanges();

            MessageBox.Show(facturaId.HasValue ? "Factura actualizada correctamente." : "Factura guardada correctamente.");
            LimpiarCampos();

            if (facturaId.HasValue)
                this.Close();
        }

        private void LimpiarCampos()
        {
            txtDesc.Clear();
            txtPrecio.Clear();
            txtItebis.Clear();
            txtDescuento.Clear();
            numCantidad.Value = 1;
            cbCategoria.SelectedIndex = 0;
        }

        private void btnVerRegistroDeFacturas_Click(object sender, EventArgs e)
        {
            this.Hide();
            using (VerFacturas verForm = new VerFacturas())
            {
                verForm.ShowDialog();
            }
        }

        private void btnCerrar_Click(object sender, EventArgs e)
        {
            var confirmar = MessageBox.Show("¿Estás seguro de que quieres salir?", "Confirmar salida", MessageBoxButtons.YesNo, MessageBoxIcon.Question);

            if (confirmar == DialogResult.Yes)
            {
                Application.Exit();
            }
        }

        private void cbCategoria_SelectedIndexChanged(object sender, EventArgs e)
        {

        }

        private void txtDesc_TextChanged(object sender, EventArgs e)
        {

        }
    }
}

```

## VerFacturas.cs
Formulario que muestra todas las facturas en un DataGridView con botones para:

#### Eliminar
#### Editar 
#### Ver reporte

```C#
using System;
using System.Data;
using System.Linq;
using System.Windows.Forms;
using SistemaFacturacion.Models;
using SistemaFacturacionCSharp;

namespace SistemaFacturacion
{
    public partial class VerFacturas : Form
    {
        private FacturaContext db = new FacturaContext();

        public VerFacturas()
        {
            InitializeComponent();
            CargarFacturas();
        }

        private void CargarFacturas()
        {
            var lista = db.FacturaDetalle
                .Select(f => new
                {
                    f.ID,
                    f.Descripcion,
                    f.Categoria,
                    f.Cantidad,
                    f.PrecioUnitario,
                    f.Itebis,
                    f.Descuento,
                    f.TotalGeneral
                }).ToList();

            dgvFacturas.DataSource = lista;
        }

        private void btnEliminar_Click(object sender, EventArgs e)
        {
            if (dgvFacturas.CurrentRow != null)
            {
                int id = (int)dgvFacturas.CurrentRow.Cells["ID"].Value;
                var factura = db.FacturaDetalle.Find(id);
                if (factura != null)
                {
                    db.FacturaDetalle.Remove(factura);
                    db.SaveChanges();
                    CargarFacturas();
                    MessageBox.Show("Factura eliminada correctamente.");
                }
            }
        }

        private void btnEditar_Click(object sender, EventArgs e)
        {
            if (dgvFacturas.CurrentRow != null)
            {
                int id = (int)dgvFacturas.CurrentRow.Cells["ID"].Value;

                var formEditar = new InsertarFactura(id);
                formEditar.ShowDialog();
                CargarFacturas();
            }
        }

        private void btnImprimir_Click(object sender, EventArgs e)
        {
            if (dgvFacturas.CurrentRow != null)
            {
                int id = (int)dgvFacturas.CurrentRow.Cells["ID"].Value;

                var reporte = new ReporteFactura(id);
                reporte.ShowDialog();
            }
        }

        private void btnVolver_Click(object sender, EventArgs e)
        {
            this.Hide();
            var form = new InsertarFactura();
            form.ShowDialog();
            this.Show();
        }

        private void dgvFacturas_CellContentClick(object sender, DataGridViewCellEventArgs e)
        {
        }

        private void VerFacturas_Load(object sender, EventArgs e)
        {

        }
    }
}
```

## ReporteFactura.cs
Formulario que usa ReportViewer para mostrar los datos de una factura específica. Usa el archivo .rdlc llamado FacturaReporte.rdlc.

``` C#
using System;
using System.Linq;
using System.Windows.Forms;
using Microsoft.Reporting.WinForms;
using SistemaFacturacion.Models;

namespace SistemaFacturacion
{
    public partial class ReporteFactura : Form
    {
        private int facturaId;

        public ReporteFactura(int id)
        {
            InitializeComponent();
            facturaId = id;
        }

        private void ReporteFactura_Load(object sender, EventArgs e)
        {
            using (var db = new FacturaContext())
            {
                var datosFactura = db.FacturaDetalle
                    .Where(f => f.ID == facturaId)
                    .Select(f => new
                    {
                        f.ID,
                        f.Descripcion,
                        f.Categoria,
                        f.Cantidad,
                        f.PrecioUnitario,
                        f.Itebis,
                        f.Descuento,
                        f.TotalGeneral
                    })
                    .ToList();

                var dataSource = new ReportDataSource("DataSetFactura", datosFactura);

                reportViewer1.LocalReport.DataSources.Clear();
                reportViewer1.LocalReport.DataSources.Add(dataSource);

                reportViewer1.LocalReport.ReportEmbeddedResource = "SistemaFacturacion.FacturaReporte.rdlc";

                reportViewer1.RefreshReport();
            }
        }

        private void reportViewer1_Load(object sender, EventArgs e)
        {

        }
    }
}
```

## 🖨️ Cómo crear el archivo RDLC
Haz clic derecho en el proyecto > Agregar > Nuevo elemento....

Busca: Report y llámalo: FacturaReporte.rdlc.

Diseña la tabla para mostrar: ID, Descripción, Categoría, Cantidad, PrecioUnitario, Itebis, Descuento, TotalGeneral.
Conéctalo al DataSet llamado DataSetFactura.

## 🗃️ Conexión con SQL Server
En FacturaContext.cs:

```C#

using System.Data.Entity;

namespace SistemaFacturacion.Models
{
    public class FacturaContext : DbContext
    {
        public FacturaContext() : base("name=ConexionFactura") { }

        public DbSet<Categoria> Categorias { get; set; }
        public DbSet<FacturaDetalle> FacturaDetalle { get; set; }

    }
}

```

## Otros Archivos:

### FacturaDetalle.cs

```C#
using System.ComponentModel.DataAnnotations;
using System.ComponentModel.DataAnnotations.Schema;

[Table("FacturaDetalle")]
public class FacturaDetalle
{
    [Key]
    public int ID { get; set; }
    public string Descripcion { get; set; }
    public string Categoria { get; set; }
    public int Cantidad { get; set; }
    public decimal PrecioUnitario { get; set; }
    public decimal Itebis { get; set; }
    public decimal Descuento { get; set; }
    public decimal TotalGeneral { get; set; }
}

```

### Categoria.cs

```C#
namespace SistemaFacturacion.Models
{
    public class Categoria
    {
        public int Id { get; set; }
        public string Nombre { get; set; }
    }
}

```

## 🧾 ¿Cómo crear un Reporte en C# con ReportViewer?


## ✅ ¿Qué es ReportViewer?

ReportViewer es una herramienta de Microsoft que permite mostrar informes (.rdlc) dentro de un formulario en C#. Puedes usarla para imprimir, exportar a PDF o simplemente mostrar datos de una base de datos de forma bonita y clara.


## 🔧 Requisitos Previos
Antes de comenzar, asegúrate de tener:

✅ Visual Studio 2022

✅ .NET Framework 4.8

✅ SQL Server (Por ejemplo mi servidor se llama AYC)

✅ Autenticación de Windows (no usas usuario ni contraseña)

✅ Base de datos creada: BD_FacturacionPruebas

✅ Tablas: FacturaDetalle y Categorias


## 🛠 Paso 1: Instalar ReportViewer
Abre Visual Studio 2022.

Ve al menú: Herramientas > Administrador de paquetes NuGet > Consola del Administrador de paquetes.

 ![imagenherr]([imagenherr.png](https://private-user-images.githubusercontent.com/151237648/445654559-9237dc99-fad9-4661-a2d4-9b1b09a15e01.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3NDc3NTE4NjksIm5iZiI6MTc0Nzc1MTU2OSwicGF0aCI6Ii8xNTEyMzc2NDgvNDQ1NjU0NTU5LTkyMzdkYzk5LWZhZDktNDY2MS1hMmQ0LTliMWIwOWExNWUwMS5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjUwNTIwJTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI1MDUyMFQxNDMyNDlaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT1hN2NmZWE3MDY4N2Q3OTBkMTU5ZjhjOGUyNTY4NjMwZTQ2NTRkNWM3YWNiNTJiMzZjNDYyZDlkYjY0ZWQ4Y2NlJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCJ9.K0Pnm5OrEKM26vKxqRgmzQoVjw4nsfQH57ISYBCWI5I))

#### Escribe y ejecuta este comando:

Install-Package Microsoft.Reporting.WinForms -Version 150.1404.0

Si da error, ve a Herramientas > Opciones > Administrador de paquetes NuGet > Orígenes de paquetes y asegúrate de que está agregado https://api.nuget.org/v3/index.json.

## 🛠 Paso 2: Crear un formulario llamado ReporteFactura.cs
Haz clic derecho en tu proyecto → Agregar > Windows Forms.

Nómbralo: ReporteFactura.cs

Haz doble clic para abrirlo.

## 🖼 Paso 3: Agregar el control ReportViewer al formulario
Abre ReporteFactura.cs en modo diseñador.

Ve a la Caja de herramientas (Toolbox).

Busca ReportViewer (si no aparece, haz clic derecho → "Elegir elementos").

Arrástralo al formulario y cambia el Dock a Fill para que ocupe todo el espacio eso lo haces dandole click derecho y dandole donde dice Propiedades.


## 📄 Paso 4: Crear el archivo .RDLC
Haz clic derecho sobre tu proyecto → Agregar > Nuevo elemento.

Selecciona Informe de Visual Studio (o Report).

Nómbralo: FacturaReporte.rdlc

Haz clic en Agregar.

## 🧩 Paso 5: Crear un DataSet para el reporte
Haz clic derecho en el proyecto → Agregar > Nuevo elemento > DataSet.

Nómbralo DataSetFactura.xsd.

Se abrirá el diseñador.

Arrastra la tabla FacturaDetalle desde el Explorador de servidores si lo tienes conectado a SQL Server, o haz clic derecho → Agregar > Tabla de datos y crea los campos manualmente:

 ![fotobd]([fotobd.png](https://private-user-images.githubusercontent.com/151237648/445654558-db2adb50-2ebd-4707-afb5-1f1cdb4eb6d2.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3NDc3NTE4NjksIm5iZiI6MTc0Nzc1MTU2OSwicGF0aCI6Ii8xNTEyMzc2NDgvNDQ1NjU0NTU4LWRiMmFkYjUwLTJlYmQtNDcwNy1hZmI1LTFmMWNkYjRlYjZkMi5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjUwNTIwJTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI1MDUyMFQxNDMyNDlaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT01YjQ0OWY5M2FmMWJiZWM0ZTk2MmE2ZjQzMmEzYTRmNDUwZTkzODM2MmJhZjQyNWRjZjA3MTQ1ODViZGNhNTMzJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCJ9.4DrpIm1thdyRzcZWF8rKlqzMZASge_SFUcXStHfY7jM))

## 📊 Paso 6: Configurar el RDLC
Abre FacturaReporte.rdlc.

Arrastra una Tabla desde el panel.

En el lado derecho, haz clic derecho → Agregar origen de datos > Objeto > DataSetFactura.

Selecciona la tabla que creaste y haz clic en Finalizar.

Asigna cada columna a un campo: Descripcion, Categoria, Cantidad, etc.

## 🧠 Paso 7: Código del formulario ReporteFactura.cs
Aquí el código completo para mostrar una factura individual en el ReportViewer:

```C#
using System;
using System.Linq;
using System.Windows.Forms;
using Microsoft.Reporting.WinForms;
using SistemaFacturacion.Models;

namespace SistemaFacturacion
{
    public partial class ReporteFactura : Form
    {
        private int facturaId;

        public ReporteFactura(int id)
        {
            InitializeComponent();
            facturaId = id;
        }

        private void ReporteFactura_Load(object sender, EventArgs e)
        {
            using (var db = new FacturaContext())
            {
                var datosFactura = db.FacturaDetalle
                    .Where(f => f.ID == facturaId)
                    .Select(f => new
                    {
                        f.ID,
                        f.Descripcion,
                        f.Categoria,
                        f.Cantidad,
                        f.PrecioUnitario,
                        f.Itebis,
                        f.Descuento,
                        f.TotalGeneral
                    })
                    .ToList();

                var dataSource = new ReportDataSource("DataSetFactura", datosFactura);

                reportViewer1.LocalReport.DataSources.Clear();
                reportViewer1.LocalReport.DataSources.Add(dataSource);

                reportViewer1.LocalReport.ReportEmbeddedResource = "SistemaFacturacion.FacturaReporte.rdlc";

                reportViewer1.RefreshReport();
            }
        }

        private void reportViewer1_Load(object sender, EventArgs e)
        {

        }
    }
}
```

Asegúrate que "SistemaFacturacion.FacturaReporte.rdlc" sea el nombre correcto con namespace. Puedes hacer clic derecho en el archivo .rdlc → Propiedades → "Ruta del recurso incrustado".

## 🧪 Paso 8: Llamar el formulario desde VerFacturas.cs
En tu botón de imprimir agrega:

```C#
        private void btnImprimir_Click(object sender, EventArgs e)
        {
            if (dgvFacturas.CurrentRow != null)
            {
                int id = (int)dgvFacturas.CurrentRow.Cells["ID"].Value;

                var reporte = new ReporteFactura(id);
                reporte.ShowDialog();
            }
        }
```

## 🖨 Resultado Final
Cuando haces clic en "Imprimir", se abrirá un formulario con el ReportViewer mostrando los datos de esa factura, listos para:

Exportar a PDF

Imprimir

Navegar entre páginas

#### Aqui tienes como deberia quedar tu reportviewer todo depende el diseno que le des.

 ![report]([report.png](https://private-user-images.githubusercontent.com/151237648/445654555-dd47f82f-a18f-4ba6-b3cf-45c5c5fc9406.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3NDc3NTE4NjksIm5iZiI6MTc0Nzc1MTU2OSwicGF0aCI6Ii8xNTEyMzc2NDgvNDQ1NjU0NTU1LWRkNDdmODJmLWExOGYtNGJhNi1iM2NmLTQ1YzVjNWZjOTQwNi5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjUwNTIwJTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI1MDUyMFQxNDMyNDlaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT05ZjJlNTQ0MzhmMmU2ZGI0MGZhYWQ0OTk1M2I5ZTk5NWQ0MjQzMmIyOGEzM2Y2NTVmMWMxZjhjNTYyNzc0MDFhJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCJ9.CHaH1lmPNtnb1MBhQ0Q1DwVeyOnDhMfbn7Zsy4eqs2Q))
