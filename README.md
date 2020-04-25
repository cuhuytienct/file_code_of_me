using Microsoft.VisualBasic;
using System;

namespace PHAN_MEM_DIEMTB
{
	class Program
	{
		static void Main(string[] args)
		{
			{
				Console.ForegroundColor = ConsoleColor.Red;
				Console.BackgroundColor = ConsoleColor.Black;
				int nums;
				double GPA = 0;
				double a, b, c, d, e, f, g, h, l, k, z, x, v, n, m;//diem chủ
				double a1, b1, c1, d1, e1, f1, g1, h1, l1, k1, z1, x1, v1, n1, m1;//so tin chi
				do
				{
					Console.WriteLine("nhap vao so mon hoc can tinh(toi da 15 mon):");
					nums = int.Parse(Console.ReadLine());
				} while (nums <= 0 || nums > 15);

				//1 môn
				if (nums == 1)
				{
					do
					{
						Console.WriteLine("nhap vao so diem chu mon hoc dat duoc:");
						a = double.Parse(Console.ReadLine());
					} while (a < 1 || a > 4);
					do
					{
						Console.WriteLine("nhap vao so tin chi mon hoc do:");
						a1 = double.Parse(Console.ReadLine());
					} while (a1 < 1 || a1 > 10);
					GPA = (a * a1) / a1;
					Console.WriteLine("GPA={0}", GPA);
				}
				// 2 môn

				if (nums == 2)
				{
					do
					{
						Console.WriteLine("nhap vao so diem chu  mon hoc 1 dat duoc:");
						a = int.Parse(Console.ReadLine());
					} while (a < 1 || a > 4);
					do
					{
						Console.WriteLine("nhap vao so diem chu mon hoc 2 dat duoc:");
						b = double.Parse(Console.ReadLine());
					} while (b < 1 || b > 4);

					do
					{
						Console.WriteLine("nhap vao so tin chi  mon hoc 1");
						a1 = double.Parse(Console.ReadLine());
					} while (a1 < 1 || a1 > 10);
					do
					{
						Console.WriteLine("nhap vao so tin chi mon hoc 2:");
						b1 = double.Parse(Console.ReadLine());
					} while (b1 < 1 || b1 > 10);

					GPA = ((a * a1) + (b * b1)) / (a1 + b1);
					Console.WriteLine("GPA={0}", GPA);
				}
				// 3 môn
				if (nums == 3)
				{
					do
					{
						Console.WriteLine("nhap vao so diem chu  mon hoc 1 dat duoc:");
						a = int.Parse(Console.ReadLine());
					} while (a < 1 || a > 4);
					do
					{
						Console.WriteLine("nhap vao so diem chu mon hoc 2 dat duoc:");
						b = double.Parse(Console.ReadLine());
					} while (b < 1 || b > 4);
					do
					{
						Console.WriteLine("nhap vao so diem chu mon hoc 3 dat duoc:");
						c = double.Parse(Console.ReadLine());
					} while (c < 1 || c > 4);

					do
					{
						Console.WriteLine("nhap vao so tin chi  mon hoc 1:");
						a1 = double.Parse(Console.ReadLine());
					} while (a1 < 1 || a1 > 10);
					do
					{
						Console.WriteLine("nhap vao so tin chi mon hoc 2:");
						b1 = double.Parse(Console.ReadLine());
					} while (b1 < 1 || b1 > 10);
					do
					{
						Console.WriteLine("nhap vao so tin chi mon hoc 3:");
						c1 = double.Parse(Console.ReadLine());
					} while (c1 < 1 || c1 > 4);

					GPA = ((a * a1) + (b * b1) + (c * c1)) / (a1 + b1 + c1);
					Console.WriteLine("GPA={0}", GPA);
				}
				//4 môn
				if (nums == 4)
				{
					do
					{
						Console.WriteLine("nhap vao so diem chu  mon hoc 1 dat duoc:");
						a = int.Parse(Console.ReadLine());
					} while (a < 1 || a > 4);
					do
					{
						Console.WriteLine("nhap vao so diem chu mon hoc 2 dat duoc:");
						b = double.Parse(Console.ReadLine());
					} while (b < 1 || b > 4);
					do
					{
						Console.WriteLine("nhap vao so diem chu mon hoc 3 dat duoc:");
						c = double.Parse(Console.ReadLine());
					} while (c < 1 || c > 4);
					do
					{
						Console.WriteLine("nhap vao so diem chu mon hoc 4 dat duoc:");
						d = double.Parse(Console.ReadLine());
					} while (d < 1 || d > 4);

					//tin chỉ
					do
					{
						Console.WriteLine("nhap vao so tin chi  mon hoc 1");
						a1 = double.Parse(Console.ReadLine());
					} while (a1 < 1 || a1 > 10);
					do
					{
						Console.WriteLine("nhap vao so tin chi mon hoc 2:");
						b1 = double.Parse(Console.ReadLine());
					} while (b1 < 1 || b1 > 10);
					do
					{
						Console.WriteLine("nhap vao so tin chi mon hoc 3:");
						c1 = double.Parse(Console.ReadLine());
					} while (c1 < 1 || c1 > 4);
					do
					{
						Console.WriteLine("nhap vao so tin chi mon hoc 4:");
						d1 = double.Parse(Console.ReadLine());
					} while (d1 < 1 || d1 > 4);
					GPA = ((a * a1) + (b * b1) + (c * c1) + (d * d1)) / (a1 + b1 + c1 + d1);
					Console.WriteLine("GPA={0}", GPA);
				}
				// 5 môn
				if (nums == 5)
				{
					do
					{
						Console.WriteLine("nhap vao so diem chu  mon hoc 1 dat duoc:");
						a = int.Parse(Console.ReadLine());
					} while (a < 1 || a > 4);
					do
					{
						Console.WriteLine("nhap vao so diem chu mon hoc 2 dat duoc:");
						b = double.Parse(Console.ReadLine());
					} while (b < 1 || b > 4);
					do
					{
						Console.WriteLine("nhap vao so diem chu mon hoc 3 dat duoc:");
						c = double.Parse(Console.ReadLine());
					} while (c < 1 || c > 4);
					do
					{
						Console.WriteLine("nhap vao so diem chu mon hoc 4 dat duoc:");
						d = double.Parse(Console.ReadLine());
					} while (d < 1 || d > 4);
					do
					{
						Console.WriteLine("nhap vao so diem chu mon hoc 5 dat duoc:");
						e = double.Parse(Console.ReadLine());
					} while (e < 1 || e > 4);

					//tin chỉ
					do
					{
						Console.WriteLine("nhap vao so tin chi  mon hoc 1");
						a1 = double.Parse(Console.ReadLine());
					} while (a1 < 1 || a1 > 10);
					do
					{
						Console.WriteLine("nhap vao so tin chi mon hoc 2:");
						b1 = double.Parse(Console.ReadLine());
					} while (b1 < 1 || b1 > 10);
					do
					{
						Console.WriteLine("nhap vao so tin chi mon hoc 3:");
						c1 = double.Parse(Console.ReadLine());
					} while (c1 < 1 || c1 > 10);
					do
					{
						Console.WriteLine("nhap vao so tin chi mon hoc 4");
						d1 = double.Parse(Console.ReadLine());
					} while (d1 < 1 || d1 > 10);
					do
					{
						Console.WriteLine("nhap vao so tin chi mon hoc 5");
						e1 = double.Parse(Console.ReadLine());
					} while (e1 < 1 || e1 > 10);
					GPA = ((a * a1) + (b * b1) + (c * c1) + (d * d1) + (e * e1)) / (a1 + b1 + c1 + d1 + e1);
					Console.WriteLine("GPA={0}", GPA);
				}
				// 6 môn
				if (nums == 6)
				{
					do
					{
						Console.WriteLine("nhap vao so diem chu  mon hoc 1 dat duoc:");
						a = int.Parse(Console.ReadLine());
					} while (a < 1 || a > 4);
					do
					{
						Console.WriteLine("nhap vao so diem chu mon hoc 2 dat duoc:");
						b = double.Parse(Console.ReadLine());
					} while (b < 1 || b > 4);
					do
					{
						Console.WriteLine("nhap vao so diem chu mon hoc 3 dat duoc:");
						c = double.Parse(Console.ReadLine());
					} while (c < 1 || c > 4);
					do
					{
						Console.WriteLine("nhap vao so diem chu mon hoc 4 dat duoc:");
						d = double.Parse(Console.ReadLine());
					} while (d < 1 || d > 4);
					do
					{
						Console.WriteLine("nhap vao so diem chu mon hoc 5 dat duoc:");
						e = double.Parse(Console.ReadLine());
					} while (e < 1 || e > 4);
					do
					{
						Console.WriteLine("nhap vao so diem chu mon hoc 6 dat duoc:");
						f = double.Parse(Console.ReadLine());
					} while (f < 1 || f > 4);

					//tin chỉ
					do
					{
						Console.WriteLine("nhap vao so tin chi  mon hoc 1:");
						a1 = double.Parse(Console.ReadLine());
					} while (a1 < 1 || a1 > 10);
					do
					{
						Console.WriteLine("nhap vao so tin chi mon hoc 2:");
						b1 = double.Parse(Console.ReadLine());
					} while (b1 < 1 || b1 > 10);
					do
					{
						Console.WriteLine("nhap vao so tin chi mon hoc 3");
						c1 = double.Parse(Console.ReadLine());
					} while (c1 < 1 || c1 > 10);
					do
					{
						Console.WriteLine("nhap vao so tin chi mon hoc 4");
						d1 = double.Parse(Console.ReadLine());
					} while (d1 < 1 || d1 > 10);
					do
					{
						Console.WriteLine("nhap vao so tin chi mon hoc 5");
						e1 = double.Parse(Console.ReadLine());
					} while (e1 < 1 || e1 > 10);
					do
					{
						Console.WriteLine("nhap vao so tin chi mon hoc 6");
						f1 = double.Parse(Console.ReadLine());
					} while (f1 < 1 || f1 > 10);
					GPA = ((a * a1) + (b * b1) + (c * c1) + (d * d1) + (e * e1) + (f * f1)) / (a1 + b1 + c1 + d1 + e1 + f1);
					Console.WriteLine("GPA={0}", GPA);
				}
				// 7 môn
				if (nums == 7)
				{
					do
					{
						Console.WriteLine("nhap vao so diem chu  mon hoc 1 dat duoc:");
						a = int.Parse(Console.ReadLine());
					} while (a < 1 || a > 4);
					do
					{
						Console.WriteLine("nhap vao so diem chu mon hoc 2 dat duoc:");
						b = double.Parse(Console.ReadLine());
					} while (b < 1 || b > 4);
					do
					{
						Console.WriteLine("nhap vao so diem chu mon hoc 3 dat duoc:");
						c = double.Parse(Console.ReadLine());
					} while (c < 1 || c > 4);
					do
					{
						Console.WriteLine("nhap vao so diem chu mon hoc 4 dat duoc:");
						d = double.Parse(Console.ReadLine());
					} while (d < 1 || d > 4);
					do
					{
						Console.WriteLine("nhap vao so diem chu mon hoc 5 dat duoc:");
						e = double.Parse(Console.ReadLine());
					} while (e < 1 || e > 4);
					do
					{
						Console.WriteLine("nhap vao so diem chu mon hoc 6 dat duoc:");
						f = double.Parse(Console.ReadLine());
					} while (f < 1 || f > 4);
					do
					{
						Console.WriteLine("nhap vao so diem chu mon hoc 7 dat duoc:");
						g = double.Parse(Console.ReadLine());
					} while (g < 1 || g > 4);

					//tin chỉ
					do
					{
						Console.WriteLine("nhap vao so tin chi  mon hoc 1");
						a1 = double.Parse(Console.ReadLine());
					} while (a1 < 1 || a1 > 10);
					do
					{
						Console.WriteLine("nhap vao so tin chi mon hoc 2:");
						b1 = double.Parse(Console.ReadLine());
					} while (b1 < 1 || b1 > 10);
					do
					{
						Console.WriteLine("nhap vao so tin chi mon hoc 3:");
						c1 = double.Parse(Console.ReadLine());
					} while (c1 < 1 || c1 > 10);
					do
					{
						Console.WriteLine("nhap vao so tin chi mon hoc 4:");
						d1 = double.Parse(Console.ReadLine());
					} while (d1 < 1 || d1 > 10);
					do
					{
						Console.WriteLine("nhap vao so tin chi mon hoc 5:");
						e1 = double.Parse(Console.ReadLine());
					} while (e1 < 1 || e1 > 10);
					do
					{
						Console.WriteLine("nhap vao so tin chi mon hoc 6");
						f1 = double.Parse(Console.ReadLine());
					} while (f1 < 1 || f1 > 10);
					do
					{
						Console.WriteLine("nhap vao so tin chi mon hoc 7");
						g1 = double.Parse(Console.ReadLine());
					} while (g1 < 1 || g1 > 10);
					GPA = ((a * a1) + (b * b1) + (c * c1) + (d * d1) + (e * e1) + (f * f1) + (g * g1)) /
				(a1 + b1 + c1 + d1 + e1 + f1 + g1);
					Console.WriteLine("GPA={0}", GPA);
				}
				// 8 môn
				if (nums == 8)
				{

					do
					{
						Console.WriteLine("nhap vao so diem chu  mon hoc 1 dat duoc:");
						a = int.Parse(Console.ReadLine());
					} while (a < 1 || a > 4);
					do
					{
						Console.WriteLine("nhap vao so diem chu mon hoc 2 dat duoc:");
						b = double.Parse(Console.ReadLine());
					} while (b < 1 || b > 4);
					do
					{
						Console.WriteLine("nhap vao so diem chu mon hoc 3 dat duoc:");
						c = double.Parse(Console.ReadLine());
					} while (c < 1 || c > 4);
					do
					{
						Console.WriteLine("nhap vao so diem chu mon hoc 4 dat duoc:");
						d = double.Parse(Console.ReadLine());
					} while (d < 1 || d > 4);
					do
					{
						Console.WriteLine("nhap vao so diem chu mon hoc 5 dat duoc:");
						e = double.Parse(Console.ReadLine());
					} while (e < 1 || e > 4);
					do
					{
						Console.WriteLine("nhap vao so diem chu mon hoc 6 dat duoc:");
						f = double.Parse(Console.ReadLine());
					} while (f < 1 || f > 4);
					do
					{
						Console.WriteLine("nhap vao so diem chu mon hoc 7 dat duoc:");
						g = double.Parse(Console.ReadLine());
					} while (g < 1 || g > 4);
					do
					{
						Console.WriteLine("nhap vao so diem chu mon hoc 8 dat duoc:");
						h = double.Parse(Console.ReadLine());
					} while (h < 1 || h > 4);
					//tin chỉ
					do
					{
						Console.WriteLine("nhap vao so tin chi  mon hoc 1");
						a1 = double.Parse(Console.ReadLine());
					} while (a1 < 1 || a1 > 10);
					do
					{
						Console.WriteLine("nhap vao so tin chi mon hoc 2:");
						b1 = double.Parse(Console.ReadLine());
					} while (b1 < 1 || b1 > 10);
					do
					{
						Console.WriteLine("nhap vao so tin chi chi mon hoc 3:");
						c1 = double.Parse(Console.ReadLine());
					} while (c1 < 1 || c1 > 10);
					do
					{
						Console.WriteLine("nhap vao so tin chi mon học 4:");
						d1 = double.Parse(Console.ReadLine());
					} while (d1 < 1 || d1 > 10);
					do
					{
						Console.WriteLine("nhap vao so tin chi mon hoc 5");
						e1 = double.Parse(Console.ReadLine());
					} while (e1 < 1 || e1 > 10);
					do
					{
						Console.WriteLine("nhap vao so tin chi mon học 6");
						f1 = double.Parse(Console.ReadLine());
					} while (f1 < 1 || f1 > 10);
					do
					{
						Console.WriteLine("nhap vao so tin chi mon hoc 7");
						g1 = double.Parse(Console.ReadLine());
					} while (g1 < 1 || g1 > 10);
					do
					{
						Console.WriteLine("nhap vao so tin chi mon hoc 8");
						h1 = double.Parse(Console.ReadLine());
					} while (h1 < 1 || h1 > 10);
					GPA = ((a * a1) + (b * b1) + (c * c1) + (d * d1) + (e * e1) + (f * f1) + (g * g1) + (h * h1)) /
			(a1 + b1 + c1 + d1 + e1 + f1 + g1 + h1);
					Console.WriteLine("GPA={0}", GPA);
				}
				// 9 môn
				if (nums == 9)
				{
					do
					{
						Console.WriteLine("nhap vao so diem chu  mon hoc 1 dat duoc:");

						a = int.Parse(Console.ReadLine());
					} while (a < 1 || a > 4);
					do
					{
						Console.WriteLine("nhap vao so diem chu mon hoc 2 dat duoc:");
						b = double.Parse(Console.ReadLine());
					} while (b < 1 || b > 4);
					do
					{
						Console.WriteLine("nhap vao so diem chu mon hoc 3 dat duoc:");
						c = double.Parse(Console.ReadLine());
					} while (c < 1 || c > 4);
					do
					{
						Console.WriteLine("nhap vao so diem chu mon hoc 4 dat duoc:");
						d = double.Parse(Console.ReadLine());
					} while (d < 1 || d > 4);
					do
					{
						Console.WriteLine("nhap vao so diem chu mon hoc 5 dat duoc:");
						e = double.Parse(Console.ReadLine());
					} while (e < 1 || e > 4);
					do
					{
						Console.WriteLine("nhap vao so diem chu mon hoc 6 dat duoc:");
						f = double.Parse(Console.ReadLine());
					} while (f < 1 || f > 4);
					do
					{
						Console.WriteLine("nhap vao so diem chu mon hoc 7 dat duoc:");
						g = double.Parse(Console.ReadLine());
					} while (g < 1 || g > 4);
					do
					{
						Console.WriteLine("nhap vao so diem chu mon hoc 8 dat duoc:");
						h = double.Parse(Console.ReadLine());
					} while (h < 1 || h > 4);
					do
					{
						Console.WriteLine("nhap vao so diem chu mon hoc 9 dat duoc:");
						l = double.Parse(Console.ReadLine());
					} while (l < 1 || l > 4);
					//tin chỉ
					do
					{
						Console.WriteLine("nhap vao so tin chi  mon hoc 1");
						a1 = double.Parse(Console.ReadLine());
					} while (a1 < 1 || a1 > 10);
					do
					{
						Console.WriteLine("nhap vao so tin chi mon hoc 2:");
						b1 = double.Parse(Console.ReadLine());
					} while (b1 < 1 || b1 > 10);
					do
					{
						Console.WriteLine("nhap vao so tin chi chi mon hoc 3:");
						c1 = double.Parse(Console.ReadLine());
					} while (c1 < 1 || c1 > 10);
					do
					{
						Console.WriteLine("nhap vao so tin chi mon học 4:");
						d1 = double.Parse(Console.ReadLine());
					} while (d1 < 1 || d1 > 10);
					do
					{
						Console.WriteLine("nhap vao so tin chi mon hoc 5");
						e1 = double.Parse(Console.ReadLine());
					} while (e1 < 1 || e1 > 10);
					do
					{
						Console.WriteLine("nhap vao so tin chi mon học 6");
						f1 = double.Parse(Console.ReadLine());
					} while (f1 < 1 || f1 > 10);
					do
					{
						Console.WriteLine("nhap vao so tin chi mon hoc 7");
						g1 = double.Parse(Console.ReadLine());
					} while (g1 < 1 || g1 > 10);
					do
					{
						Console.WriteLine("nhap vao so tin chi mon hoc 8");
						h1 = double.Parse(Console.ReadLine());
					} while (h1 < 1 || h1 > 10);
					do
					{
						Console.WriteLine("nhap vao so tin chi mon hoc 8");
						l1 = double.Parse(Console.ReadLine());
					} while (l1 < 1 || l1 > 10);
					GPA = ((a * a1) + (b * b1) + (c * c1) + (d * d1) + (e * e1) + (f * f1) + (g * g1) + (h * h1) + (l * l1)) /
				   (a1 + b1 + c1 + d1 + e1 + f1 + g1 + h1 + l1);
					Console.WriteLine("GPA={0}", GPA);
				}


				// 10 môn
				// diểm chữ
				if (nums == 10)
				{
					do
					{
						Console.WriteLine("nhap vao so diem chu  mon hoc 1 dat duoc:");
						a = int.Parse(Console.ReadLine());
					} while (a < 1 || a > 4);
					do
					{
						Console.WriteLine("nhap vao so diem chu mon hoc 2 dat duoc:");
						b = double.Parse(Console.ReadLine());
					} while (b < 1 || b > 4);
					do
					{
						Console.WriteLine("nhap vao so diem chu  mon hoc 3 dat duoc:");
						c = int.Parse(Console.ReadLine());
					} while (c < 1 || c > 4);
					do
					{
						Console.WriteLine("nhap vao so diem chu mon hoc 4 dat duoc:");
						d = double.Parse(Console.ReadLine());
					} while (d < 1 || d > 4);
					do
					{
						Console.WriteLine("nhap vao so diem chu  mon hoc 5 dat duoc:");
						e = int.Parse(Console.ReadLine());
					} while (e < 1 || e > 4);
					do
					{
						Console.WriteLine("nhap vao so diem chu mon hoc 6 dat duoc:");
						f = double.Parse(Console.ReadLine());
					} while (f < 1 || f > 4);
					do
					{
						Console.WriteLine("nhap vao so diem chu  mon hoc 7 dat duoc:");
						g = int.Parse(Console.ReadLine());
					} while (g < 1 || g > 4);
					do
					{
						Console.WriteLine("nhap vao so diem chu mon hoc 8 dat duoc:");
						h = double.Parse(Console.ReadLine());
					} while (h < 1 || h > 4);
					do
					{
						Console.WriteLine("nhap vao so diem chu  mon hoc 9 dat duoc:");
						l = int.Parse(Console.ReadLine());
					} while (l < 1 || l > 4);
					do
					{
						Console.WriteLine("nhap vao so diem chu mon hoc 10 dat duoc:");
						k = double.Parse(Console.ReadLine());
					} while (k < 1 || k > 4);

					// tín chỉ
					do
					{
						Console.WriteLine("nhap vao so tin chi  mon hoc 1");
						a1 = double.Parse(Console.ReadLine());
					} while (a1 < 1 || a1 > 10);
					do
					{
						Console.WriteLine("nhap vao so tin chi mon hoc 2:");
						b1 = double.Parse(Console.ReadLine());
					} while (b1 < 1 || b1 > 10);
					do
					{
						Console.WriteLine("nhap vao so tin chi  mon hoc 3");
						c1 = double.Parse(Console.ReadLine());
					} while (c1 < 1 || c1 > 10);
					do
					{
						Console.WriteLine("nhap vao so tin chi mon hoc 4:");
						d1 = double.Parse(Console.ReadLine());
					} while (d1 < 1 || d1 > 10);
					do
					{
						Console.WriteLine("nhap vao so tin chi  mon hoc 5");
						e1 = double.Parse(Console.ReadLine());
					} while (e1 < 1 || e1 > 10);
					do
					{
						Console.WriteLine("nhap vao so tin chi mon hoc 6:");
						f1 = double.Parse(Console.ReadLine());
					} while (f1 < 1 || f1 > 10);
					do
					{
						Console.WriteLine("nhap vao so tin chi  mon hoc 7");
						g1 = double.Parse(Console.ReadLine());
					} while (g1 < 1 || g1 > 10);
					do
					{
						Console.WriteLine("nhap vao so tin chi mon hoc 8:");
						h1 = double.Parse(Console.ReadLine());
					} while (h1 < 1 || h1 > 10);
					do
					{
						Console.WriteLine("nhap vao so tin chi  mon hoc 9");
						l1 = double.Parse(Console.ReadLine());
					} while (l1 < 1 || l1 > 10);
					do
					{
						Console.WriteLine("nhap vao so tin chi mon hoc 10:");
						k1 = double.Parse(Console.ReadLine());
					} while (k1 < 1 || k1 > 10);
					GPA = ((a * a1) + (b * b1) + (c * c1) + (d * d1) + (e * e1) + (f * f1) + (g * g1) + (h * h1) + (l * l1) + (k * k1)) /
					(a1 + b1 + c1 + d1 + e1 + f1 + g1 + h1 + l1 + k1);
					Console.WriteLine("GPA={0}", GPA);
				}

				// 11 môn
				if (nums == 11)
				{
					// diểm chữ
					do
					{
						Console.WriteLine("nhap vao so diem chu  mon hoc 1 dat duoc:");
						a = int.Parse(Console.ReadLine());
					} while (a < 1 || a > 4);
					do
					{
						Console.WriteLine("nhap vao so diem chu mon hoc 2 dat duoc:");
						b = double.Parse(Console.ReadLine());
					} while (b < 1 || b > 4);
					do
					{
						Console.WriteLine("nhap vao so diem chu  mon hoc 3 dat duoc:");
						c = int.Parse(Console.ReadLine());
					} while (c < 1 || c > 4);
					do
					{
						Console.WriteLine("nhap vao so diem chu mon hoc 4 dat duoc:");
						d = double.Parse(Console.ReadLine());
					} while (d < 1 || d > 4);
					do
					{
						Console.WriteLine("nhap vao so diem chu  mon hoc 5 dat duoc:");
						e = int.Parse(Console.ReadLine());
					} while (e < 1 || e > 4);
					do
					{
						Console.WriteLine("nhap vao so diem chu mon hoc 6 dat duoc:");
						f = double.Parse(Console.ReadLine());
					} while (f < 1 || f > 4);
					do
					{
						Console.WriteLine("nhap vao so diem chu  mon hoc 7 dat duoc:");
						g = int.Parse(Console.ReadLine());
					} while (g < 1 || g > 4);
					do
					{
						Console.WriteLine("nhap vao so diem chu mon hoc 8 dat duoc:");
						h = double.Parse(Console.ReadLine());
					} while (h < 1 || h > 4);
					do
					{
						Console.WriteLine("nhap vao so diem chu  mon hoc 9 dat duoc:");
						l = int.Parse(Console.ReadLine());
					} while (l < 1 || l > 4);
					do
					{
						Console.WriteLine("nhap vao so diem chu mon hoc 10 dat duoc:");
						k = double.Parse(Console.ReadLine());
					} while (k < 1 || k > 4);
					do
					{
						Console.WriteLine("nhap vao so diem chu  mon hoc 11 dat duoc:");
						z = int.Parse(Console.ReadLine());
					} while (z < 1 || z > 4);
					// tín chỉ
					do
					{
						Console.WriteLine("nhap vao so tin chi  mon hoc 1");
						a1 = double.Parse(Console.ReadLine());
					} while (a1 < 1 || a1 > 10);
					do
					{
						Console.WriteLine("nhap vao so tin chi mon hoc 2:");
						b1 = double.Parse(Console.ReadLine());
					} while (b1 < 1 || b1 > 10);
					do
					{
						Console.WriteLine("nhap vao so tin chi  mon hoc 3");
						c1 = double.Parse(Console.ReadLine());
					} while (c1 < 1 || c1 > 10);
					do
					{
						Console.WriteLine("nhap vao so tin chi mon hoc 4:");
						d1 = double.Parse(Console.ReadLine());
					} while (d1 < 1 || d1 > 10);
					do
					{
						Console.WriteLine("nhap vao so tin chi  mon hoc 5");
						e1 = double.Parse(Console.ReadLine());
					} while (e1 < 1 || e1 > 10);
					do
					{
						Console.WriteLine("nhap vao so tin chi mon hoc 6:");
						f1 = double.Parse(Console.ReadLine());
					} while (f1 < 1 || f1 > 10);
					do
					{
						Console.WriteLine("nhap vao so tin chi  mon hoc 7");
						g1 = double.Parse(Console.ReadLine());
					} while (g1 < 1 || g1 > 10);
					do
					{
						Console.WriteLine("nhap vao so tin chi mon hoc 8:");
						h1 = double.Parse(Console.ReadLine());
					} while (h1 < 1 || h1 > 10);
					do
					{
						Console.WriteLine("nhap vao so tin chi  mon hoc 9");
						l1 = double.Parse(Console.ReadLine());
					} while (l1 < 1 || l1 > 10);
					do
					{
						Console.WriteLine("nhap vao so tin chi mon hoc 10:");
						k1 = double.Parse(Console.ReadLine());
					} while (k1 < 1 || k1 > 10);
					do
					{
						Console.WriteLine("nhap vao so tin chi  mon hoc 11");
						z1 = double.Parse(Console.ReadLine());
					} while (z1 < 1 || z1 > 10);
					GPA = ((a * a1) + (b * b1) + (c * c1) + (d * d1) + (e * e1) + (f * f1) + (g * g1) + (h * h1) + (l * l1) +
						(k * k1) + (z * z1)) / (a1 + b1 + c1 + d1 + e1 + f1 + g1 + h1 + l1 + k1 + z1);
					Console.WriteLine("GPA={0}", GPA);
				}
				//12 môn
				if (nums == 12)
				{
					// diểm chữ
					do
					{
						Console.WriteLine("nhap vao so diem chu  mon hoc 1 dat duoc:");
						a = int.Parse(Console.ReadLine());
					} while (a < 1 || a > 4);
					do
					{
						Console.WriteLine("nhap vao so diem chu mon hoc 2 dat duoc:");
						b = double.Parse(Console.ReadLine());
					} while (b < 1 || b > 4);
					do
					{
						Console.WriteLine("nhap vao so diem chu  mon hoc 3 dat duoc:");
						c = int.Parse(Console.ReadLine());
					} while (c < 1 || c > 4);
					do
					{
						Console.WriteLine("nhap vao so diem chu mon hoc 4 dat duoc:");
						d = double.Parse(Console.ReadLine());
					} while (d < 1 || d > 4);
					do
					{
						Console.WriteLine("nhap vao so diem chu  mon hoc 5 dat duoc:");
						e = int.Parse(Console.ReadLine());
					} while (e < 1 || e > 4);
					do
					{
						Console.WriteLine("nhap vao so diem chu mon hoc 6 dat duoc:");
						f = double.Parse(Console.ReadLine());
					} while (f < 1 || f > 4);
					do
					{
						Console.WriteLine("nhap vao so diem chu  mon hoc 7 dat duoc:");
						g = int.Parse(Console.ReadLine());
					} while (g < 1 || g > 4);
					do
					{
						Console.WriteLine("nhap vao so diem chu mon hoc 8 dat duoc:");
						h = double.Parse(Console.ReadLine());
					} while (h < 1 || h > 4);
					do
					{
						Console.WriteLine("nhap vao so diem chu  mon hoc 9 dat duoc:");
						l = int.Parse(Console.ReadLine());
					} while (l < 1 || l > 4);
					do
					{
						Console.WriteLine("nhap vao so diem chu mon hoc 10 dat duoc:");
						k = double.Parse(Console.ReadLine());
					} while (k < 1 || k > 4);
					do
					{
						Console.WriteLine("nhap vao so diem chu  mon hoc 11 dat duoc:");
						z = int.Parse(Console.ReadLine());
					} while (z < 1 || z > 4);
					do
					{
						Console.WriteLine("nhap vao so diem chu mon hoc 12 dat duoc:");
						x = double.Parse(Console.ReadLine());
					} while (x < 1 || x > 4);

					// tín chỉ
					do
					{
						Console.WriteLine("nhap vao so tin chi  mon hoc 1");
						a1 = double.Parse(Console.ReadLine());
					} while (a1 < 1 || a1 > 10);
					do
					{
						Console.WriteLine("nhap vao so tin chi mon hoc 2:");
						b1 = double.Parse(Console.ReadLine());
					} while (b1 < 1 || b1 > 10);
					do
					{
						Console.WriteLine("nhap vao so tin chi  mon hoc 3");
						c1 = double.Parse(Console.ReadLine());
					} while (c1 < 1 || c1 > 10);
					do
					{
						Console.WriteLine("nhap vao so tin chi mon hoc 4:");
						d1 = double.Parse(Console.ReadLine());
					} while (d1 < 1 || d1 > 10);
					do
					{
						Console.WriteLine("nhap vao so tin chi  mon hoc 5:");
						e1 = double.Parse(Console.ReadLine());
					} while (e1 < 1 || e1 > 10);
					do
					{
						Console.WriteLine("nhap vao so tin chi mon hoc 6:");
						f1 = double.Parse(Console.ReadLine());
					} while (f1 < 1 || f1 > 10);
					do
					{
						Console.WriteLine("nhap vao so tin chi  mon hoc 7:");
						g1 = double.Parse(Console.ReadLine());
					} while (g1 < 1 || g1 > 10);
					do
					{
						Console.WriteLine("nhap vao so tin chi mon hoc 8:");
						h1 = double.Parse(Console.ReadLine());
					} while (h1 < 1 || h1 > 10);
					do
					{
						Console.WriteLine("nhap vao so tin chi  mon hoc 9:");
						l1 = double.Parse(Console.ReadLine());
					} while (l1 < 1 || l1 > 10);
					do
					{
						Console.WriteLine("nhap vao so tin chi mon hoc 10:");
						k1 = double.Parse(Console.ReadLine());
					} while (k1 < 1 || k1 > 10);
					do
					{
						Console.WriteLine("nhap vao so tin chi  mon hoc 11:");
						z1 = double.Parse(Console.ReadLine());
					} while (z1 < 1 || z1 > 10);
					do
					{
						Console.WriteLine("nhap vao so tin chi mon hoc 12:");
						x1 = double.Parse(Console.ReadLine());
					} while (x1 < 1 || x1 > 10);
					GPA = ((a * a1) + (b * b1) + (c * c1) + (d * d1) + (e * e1) + (f * f1) + (g * g1) + (h * h1) + (l * l1) + (k * k1)
						+ (z * z1) + (x * x1)) / (a1 + b1 + c1 + d1 + e1 + f1 + g1 + h1 + l1 + k1 + z1 + x1);
					Console.WriteLine("GPA={0}", GPA);
				}

				// 13 môn
				if (nums == 13)
				{
					// diểm chữ
					do
					{
						Console.WriteLine("nhap vao so diem chu  mon hoc 1 dat duoc:");
						a = int.Parse(Console.ReadLine());
					} while (a < 1 || a > 4);
					do
					{
						Console.WriteLine("nhap vao so diem chu mon hoc 2 dat duoc:");
						b = double.Parse(Console.ReadLine());
					} while (b < 1 || b > 4);
					do
					{
						Console.WriteLine("nhap vao so diem chu  mon hoc 3 dat duoc:");
						c = int.Parse(Console.ReadLine());
					} while (c < 1 || c > 4);
					do
					{
						Console.WriteLine("nhap vao so diem chu mon hoc 4 dat duoc:");
						d = double.Parse(Console.ReadLine());
					} while (d < 1 || d > 4);
					do
					{
						Console.WriteLine("nhap vao so diem chu  mon hoc 5 dat duoc:");
						e = int.Parse(Console.ReadLine());
					} while (e < 1 || e > 4);
					do
					{
						Console.WriteLine("nhap vao so diem chu mon hoc 6 dat duoc:");
						f = double.Parse(Console.ReadLine());
					} while (f < 1 || f > 4);
					do
					{
						Console.WriteLine("nhap vao so diem chu  mon hoc 7 dat duoc:");
						g = int.Parse(Console.ReadLine());
					} while (g < 1 || g > 4);
					do
					{
						Console.WriteLine("nhap vao so diem chu mon hoc 8 dat duoc:");
						h = double.Parse(Console.ReadLine());
					} while (h < 1 || h > 4);
					do
					{
						Console.WriteLine("nhap vao so diem chu  mon hoc 9 dat duoc:");
						l = int.Parse(Console.ReadLine());
					} while (l < 1 || l > 4);
					do
					{
						Console.WriteLine("nhap vao so diem chu mon hoc 10 dat duoc:");
						k = double.Parse(Console.ReadLine());
					} while (k < 1 || k > 4);
					do
					{
						Console.WriteLine("nhap vao so diem chu  mon hoc 11 dat duoc:");
						z = int.Parse(Console.ReadLine());
					} while (z < 1 || z > 4);
					do
					{
						Console.WriteLine("nhap vao so diem chu mon hoc 12 dat duoc:");
						x = double.Parse(Console.ReadLine());
					} while (x < 1 || x > 4);
					do
					{
						Console.WriteLine("nhap vao so diem chu  mon hoc 13 dat duoc:");
						v = int.Parse(Console.ReadLine());
					} while (v < 1 || v > 4);
					// tín chỉ
					do
					{
						Console.WriteLine("nhap vao so tin chi  mon hoc 1");
						a1 = double.Parse(Console.ReadLine());
					} while (a1 < 1 || a1 > 10);
					do
					{
						Console.WriteLine("nhap vao so tin chi mon hoc 2:");
						b1 = double.Parse(Console.ReadLine());
					} while (b1 < 1 || b1 > 10);
					do
					{
						Console.WriteLine("nhap vao so tin chi  mon hoc 3");
						c1 = double.Parse(Console.ReadLine());
					} while (c1 < 1 || c1 > 10);
					do
					{
						Console.WriteLine("nhap vao so tin chi mon hoc 4:");
						d1 = double.Parse(Console.ReadLine());
					} while (d1 < 1 || d1 > 10);
					do
					{
						Console.WriteLine("nhap vao so tin chi  mon hoc 5");
						e1 = double.Parse(Console.ReadLine());
					} while (e1 < 1 || e1 > 10);
					do
					{
						Console.WriteLine("nhap vao so tin chi mon hoc 6:");
						f1 = double.Parse(Console.ReadLine());
					} while (f1 < 1 || f1 > 10);
					do
					{
						Console.WriteLine("nhap vao so tin chi  mon hoc 7");
						g1 = double.Parse(Console.ReadLine());
					} while (g1 < 1 || g1 > 10);
					do
					{
						Console.WriteLine("nhap vao so tin chi mon hoc 8:");
						h1 = double.Parse(Console.ReadLine());
					} while (h1 < 1 || h1 > 10);
					do
					{
						Console.WriteLine("nhap vao so tin chi  mon hoc 9");
						l1 = double.Parse(Console.ReadLine());
					} while (l1 < 1 || l1 > 10);
					do
					{
						Console.WriteLine("nhap vao so tin chi mon hoc 10:");
						k1 = double.Parse(Console.ReadLine());
					} while (k1 < 1 || k1 > 10);
					do
					{
						Console.WriteLine("nhap vao so tin chi  mon hoc 11");
						z1 = double.Parse(Console.ReadLine());
					} while (z1 < 1 || z1 > 10);
					do
					{
						Console.WriteLine("nhap vao so tin chi mon hoc 12:");
						x1 = double.Parse(Console.ReadLine());
					} while (x1 < 1 || x1 > 10);
					do
					{
						Console.WriteLine("nhap vao so tin chi  mon hoc 13");
						v1 = double.Parse(Console.ReadLine());
					} while (v1 < 1 || v1 > 10);
					GPA = ((a * a1) + (b * b1) + (c * c1) + (d * d1) + (e * e1) + (f * f1) + (g * g1) + (h * h1) + (l * l1) + (k * k1) + (z * z1) + (x * x1) + (v * v1)) /
						(a1 + b1 + c1 + d1 + e1 + f1 + g1 + h1 + l1 + k1 + z1 + x1 + v1);
					Console.WriteLine("GPA={0}", GPA);
				}


				// 14 môn
				if (nums == 14)
				{
					// diểm chữ
					do
					{
						Console.WriteLine("nhap vao so diem chu  mon hoc 1 dat duoc:");
						a = int.Parse(Console.ReadLine());
					} while (a < 1 || a > 4);
					do
					{
						Console.WriteLine("nhap vao so diem chu mon hoc 2 dat duoc:");
						b = double.Parse(Console.ReadLine());
					} while (b < 1 || b > 4);
					do
					{
						Console.WriteLine("nhap vao so diem chu  mon hoc 3 dat duoc:");
						c = int.Parse(Console.ReadLine());
					} while (c < 1 || c > 4);
					do
					{
						Console.WriteLine("nhap vao so diem chu mon hoc 4 dat duoc:");
						d = double.Parse(Console.ReadLine());
					} while (d < 1 || d > 4);
					do
					{
						Console.WriteLine("nhap vao so diem chu  mon hoc 5 dat duoc:");
						e = int.Parse(Console.ReadLine());
					} while (e < 1 || e > 4);
					do
					{
						Console.WriteLine("nhap vao so diem chu mon hoc 6 dat duoc:");
						f = double.Parse(Console.ReadLine());
					} while (f < 1 || f > 4);
					do
					{
						Console.WriteLine("nhap vao so diem chu  mon hoc 7 dat duoc:");
						g = int.Parse(Console.ReadLine());
					} while (g < 1 || g > 4);
					do
					{
						Console.WriteLine("nhap vao so diem chu mon hoc 8 dat duoc:");
						h = double.Parse(Console.ReadLine());
					} while (h < 1 || h > 4);
					do
					{
						Console.WriteLine("nhap vao so diem chu  mon hoc 9 dat duoc:");
						l = int.Parse(Console.ReadLine());
					} while (l < 1 || l > 4);
					do
					{
						Console.WriteLine("nhap vao so diem chu mon hoc 10 dat duoc:");
						k = double.Parse(Console.ReadLine());
					} while (k < 1 || k > 4);
					do
					{
						Console.WriteLine("nhap vao so diem chu  mon hoc 11 dat duoc:");
						z = int.Parse(Console.ReadLine());
					} while (z < 1 || z > 4);
					do
					{
						Console.WriteLine("nhap vao so diem chu mon hoc 12 dat duoc:");
						x = double.Parse(Console.ReadLine());
					} while (x < 1 || x > 4);
					do
					{
						Console.WriteLine("nhap vao so diem chu  mon hoc 13 dat duoc:");
						v = int.Parse(Console.ReadLine());
					} while (v < 1 || v > 4);
					do
					{
						Console.WriteLine("nhap vao so diem chu mon hoc 14 dat duoc:");
						n = double.Parse(Console.ReadLine());
					} while (n < 1 || n > 4);
					// tín chỉ
					do
					{
						Console.WriteLine("nhap vao so tin chi  mon hoc 1");
						a1 = double.Parse(Console.ReadLine());
					} while (a1 < 1 || a1 > 10);
					do
					{
						Console.WriteLine("nhap vao so tin chi mon hoc 2:");
						b1 = double.Parse(Console.ReadLine());
					} while (b1 < 1 || b1 > 10);
					do
					{
						Console.WriteLine("nhap vao so tin chi  mon hoc 3");
						c1 = double.Parse(Console.ReadLine());
					} while (c1 < 1 || c1 > 10);
					do
					{
						Console.WriteLine("nhap vao so tin chi mon hoc 4:");
						d1 = double.Parse(Console.ReadLine());
					} while (d1 < 1 || d1 > 10);
					do
					{
						Console.WriteLine("nhap vao so tin chi  mon hoc 5:");
						e1 = double.Parse(Console.ReadLine());
					} while (e1 < 1 || e1 > 10);
					do
					{
						Console.WriteLine("nhap vao so tin chi mon hoc 6:");
						f1 = double.Parse(Console.ReadLine());
					} while (f1 < 1 || f1 > 10);
					do
					{
						Console.WriteLine("nhap vao so tin chi  mon hoc 7:");
						g1 = double.Parse(Console.ReadLine());
					} while (g1 < 1 || g1 > 10);
					do
					{
						Console.WriteLine("nhap vao so tin chi mon hoc 8:");
						h1 = double.Parse(Console.ReadLine());
					} while (h1 < 1 || h1 > 10);
					do
					{
						Console.WriteLine("nhap vao so tin chi  mon hoc 9:");
						l1 = double.Parse(Console.ReadLine());
					} while (l1 < 1 || l1 > 10);
					do
					{
						Console.WriteLine("nhap vao so tin chi mon hoc 10:");
						k1 = double.Parse(Console.ReadLine());
					} while (k1 < 1 || k1 > 10);
					do
					{
						Console.WriteLine("nhap vao so tin chi  mon hoc 11");
						z1 = double.Parse(Console.ReadLine());
					} while (z1 < 1 || z1 > 10);
					do
					{
						Console.WriteLine("nhap vao so tin chi mon hoc 12:");
						x1 = double.Parse(Console.ReadLine());
					} while (x1 < 1 || x1 > 10);
					do
					{
						Console.WriteLine("nhap vao so tin chi  mon hoc 13");
						v1 = double.Parse(Console.ReadLine());
					} while (v1 < 1 || v1 > 10);
					do
					{
						Console.WriteLine("nhap vao so tin chi mon hoc 14:");
						n1 = double.Parse(Console.ReadLine());
					} while (n1 < 1 || n1 > 10);
					GPA = ((a * a1) + (b * b1) + (c * c1) + (d * d1) + (e * e1) + (f * f1) + (g * g1) + (h * h1) + (l * l1) +
					(k * k1) + (z * z1) + (x * x1) + (v * v1) + (n * n1)) / (a1 + b1 + c1 + d1 + e1 + f1 + g1 + h1 + l1 + k1 + z1 + x1 + v1 + n1);
					Console.WriteLine("GPA={0}", GPA);
				}


				if (nums == 15)
				{
					// diểm chữ
					do
					{
						Console.WriteLine("nhap vao so diem chu  mon hoc 1 dat duoc:");
						a = int.Parse(Console.ReadLine());
					} while (a < 1 || a > 4);
					do
					{
						Console.WriteLine("nhap vao so diem chu mon hoc 2 dat duoc:");
						b = double.Parse(Console.ReadLine());
					} while (b < 1 || b > 4);
					do
					{
						Console.WriteLine("nhap vao so diem chu  mon hoc 3 dat duoc:");
						c = int.Parse(Console.ReadLine());
					} while (c < 1 || c > 4);
					do
					{
						Console.WriteLine("nhap vao so diem chu mon hoc 4 dat duoc:");
						d = double.Parse(Console.ReadLine());
					} while (d < 1 || d > 4);
					do
					{
						Console.WriteLine("nhap vao so diem chu  mon hoc 5 dat duoc:");
						e = int.Parse(Console.ReadLine());
					} while (e < 1 || e > 4);
					do
					{
						Console.WriteLine("nhap vao so diem chu mon hoc 6 dat duoc:");
						f = double.Parse(Console.ReadLine());
					} while (f < 1 || f > 4);
					do
					{
						Console.WriteLine("nhap vao so diem chu  mon hoc 7 dat duoc:");
						g = int.Parse(Console.ReadLine());
					} while (g < 1 || g > 4);
					do
					{
						Console.WriteLine("nhap vao so diem chu mon hoc 8 dat duoc:");
						h = double.Parse(Console.ReadLine());
					} while (h < 1 || h > 4);
					do
					{
						Console.WriteLine("nhap vao so diem chu  mon hoc 9 dat duoc:");
						l = int.Parse(Console.ReadLine());
					} while (l < 1 || l > 4);
					do
					{
						Console.WriteLine("nhap vao so diem chu mon hoc 10 dat duoc:");
						k = double.Parse(Console.ReadLine());
					} while (k < 1 || k > 4);
					do
					{
						Console.WriteLine("nhap vao so diem chu  mon hoc 11 dat duoc:");
						z = int.Parse(Console.ReadLine());
					} while (z < 1 || z > 4);
					do
					{
						Console.WriteLine("nhap vao so diem chu mon hoc 12 dat duoc:");
						x = double.Parse(Console.ReadLine());
					} while (x < 1 || x > 4);
					do
					{
						Console.WriteLine("nhap vao so diem chu  mon hoc 13 dat duoc:");
						v = int.Parse(Console.ReadLine());
					} while (v < 1 || v > 4);
					do
					{
						Console.WriteLine("nhap vao so diem chu mon hoc 14 dat duoc:");
						n = double.Parse(Console.ReadLine());
					} while (n < 1 || n > 4);
					do
					{
						Console.WriteLine("nhap vao so diem chu mon hoc 15 dat duoc:");
						m = double.Parse(Console.ReadLine());
					} while (m < 1 || m > 4);
					// tín chỉ

					do
					{
						Console.WriteLine("nhap vao so tin chi  mon hoc 1");
						a1 = double.Parse(Console.ReadLine());
					} while (a1 < 1 || a1 > 10);
					do
					{
						Console.WriteLine("nhap vao so tin chi mon hoc 2:");
						b1 = double.Parse(Console.ReadLine());
					} while (b1 < 1 || b1 > 10);
					do
					{
						Console.WriteLine("nhap vao so tin chi  mon hoc 3");
						c1 = double.Parse(Console.ReadLine());
					} while (c1 < 1 || c1 > 10);
					do
					{
						Console.WriteLine("nhap vao so tin chi mon hoc 4:");
						d1 = double.Parse(Console.ReadLine());
					} while (d1 < 1 || d1 > 10);
					do
					{
						Console.WriteLine("nhap vao so tin chi  mon hoc 5");
						e1 = double.Parse(Console.ReadLine());
					} while (e1 < 1 || e1 > 10);
					do
					{
						Console.WriteLine("nhap vao so tin chi mon hoc 6:");
						f1 = double.Parse(Console.ReadLine());
					} while (f1 < 1 || f1 > 10);
					do
					{
						Console.WriteLine("nhap vao so tin chi  mon hoc 7:");
						g1 = double.Parse(Console.ReadLine());
					} while (g1 < 1 || g1 > 10);
					do
					{
						Console.WriteLine("nhap vao so tin chi mon hoc 8:");
						h1 = double.Parse(Console.ReadLine());
					} while (h1 < 1 || h1 > 10);
					do
					{
						Console.WriteLine("nhap vao so tin chi  mon hoc 9:");
						l1 = double.Parse(Console.ReadLine());
					} while (l1 < 1 || l1 > 10);
					do
					{
						Console.WriteLine("nhap vao so tin chi mon hoc 10:");
						k1 = double.Parse(Console.ReadLine());
					} while (k1 < 1 || k1 > 10);
					do
					{
						Console.WriteLine("nhap vao so tin chi  mon hoc 11");
						z1 = double.Parse(Console.ReadLine());
					} while (z1 < 1 || z1 > 10);
					do
					{
						Console.WriteLine("nhap vao so tin chi mon hoc 12:");
						x1 = double.Parse(Console.ReadLine());
					} while (x1 < 1 || x1 > 10);
					do
					{
						Console.WriteLine("nhap vao so tin chi  mon hoc 13");
						v1 = double.Parse(Console.ReadLine());
					} while (v1 < 1 || v1 > 10);
					do
					{
						Console.WriteLine("nhap vao so tin chi mon hoc 14:");
						n1 = double.Parse(Console.ReadLine());
					} while (n1 < 1 || n1 > 10);
					do
					{
						Console.WriteLine("nhap vao so tin chi  mon hoc 15");
						m1 = double.Parse(Console.ReadLine());
					} while (m1 < 1 || m1 > 10);
					GPA = ((a * a1) + (b * b1) + (c * c1) + (d * d1) + (e * e1) + (f * f1) + (g * g1) + (h * h1) + (l * l1) + (k * k1) + (z * z1) + (x * x1) + (v * v1) + (n * n1) + (m * m1)) /
						(a1 + b1 + c1 + d1 + e1 + f1 + g1 + h1 + l1 + k1 + z1 + x1 + v1 + n1 + m1);
					Console.WriteLine("GPA={0}", GPA);
				}

				if (GPA < 1)
				{
					Console.WriteLine("XL KEM");
				}
				if (GPA >= 1 && GPA <= 1.49)
				{
					Console.WriteLine("XL YEU");
				}
				if (GPA >= 1.5 && GPA <= 1.99)
				{
					Console.Write("XL TRUNG BINH YEU");
				}
				if (GPA >= 2 && GPA <= 2.29)
				{
					Console.WriteLine("XL TRUNG BINH");
				}
				if (GPA >= 2.3 && GPA <= 2.49)
				{
					Console.WriteLine("XL TRUNG BINH KHA");
				}
				if (GPA >= 2.5 && GPA <= 3.19)
				{
					Console.WriteLine("XL  KHA");
				}
				if (GPA >= 3.2 && GPA <= 3.59)
				{
					Console.WriteLine("XL GIOI");
				}
				if (GPA >= 3.6 && GPA <= 4.0)
				{
					Console.WriteLine("XL XUAT SAC");
				}
			}
		}
	}
}
				

