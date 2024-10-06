using System;
using System.Collections.Generic;
using System.ComponentModel;
using System.Data;
using System.Drawing;
using System.Linq;
using System.Text;
using System.Threading.Tasks;
using System.Windows.Forms;
using System.Xml.Schema;

namespace Student_Grade_Calculator
{
    public partial class Form1 : Form
    {
        public Form1()
        {
            InitializeComponent();
        }

        private void button1_Click(object sender, EventArgs e)
        {
            double Math, Physics, Chemistry,Total,Avg;
            string grade;
            Math=int.Parse(textBox1.Text);
            Physics=int.Parse(textBox2.Text);
            Chemistry=int.Parse(textBox3.Text);
           Total= Math+Physics+Chemistry;
        
            txtTot.Text=textBox4.Text;
            Avg = Total / 3;
            txtAvg.Text=textBox5.Text;
            if (Avg >= 80)
            {
                grade = "A+";
                grade = textBox4.Text;
            }
            else if (Avg >= 70 && Avg <= 79)
            {
                grade = "A";
                grade = textBox4.Text;
            }
            else if (Avg >= 60 && Avg <= 69)
            {
                grade = "A-";
                grade = textBox4.Text;
            }
            else if(Avg >=50&&Avg<=59)
            {
                grade = "B";
                grade = textBox4.Text;
            }
            else if (Avg >=40&&Avg<=49)
            {
                grade = "C";
                grade = textBox4.Text;
            }
            else if(Avg<40)
            {
                grade = "F";
                grade=textBox4.Text;
            }
            

        }
    }
}
