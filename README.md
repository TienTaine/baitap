

void bt19()
{
	int soGio, thoiDiem, ngay,loaiPhong,tien;
	cout << "Nhap so gio thue phong: " << endl;
	cin >> soGio;
	cout << "Nhap thoi diem thue phong: " << endl;
	cin >> thoiDiem;
	cout << "Nhap ngay thue phong: " << endl;
	cout << " Chu Nhat nhap 8" << endl;
	cin >> ngay;
	cout << "Nhap loai phong: " << endl;
	cout << " 1 : Phong Vip " << endl;
	cout << " 2 : Phong Thuong " << endl;
	cin >> loaiPhong;
	if (ngay < 2 || ngay > 8)
	{
		cout << "Moi nhap lai ngay ";
	}
	else
	if (loaiPhong == 1)
	{
		if (ngay >= 2 && ngay <= 6)
		{
			if (thoiDiem >= 10 && thoiDiem <= 18)
			{
				tien = 100000 * soGio;
				cout << "So tien: " << tien;
			}

			else
				if (thoiDiem > 18)
				{
					tien = 300000 * soGio;
					cout << "So tien: " << tien;
				}
		}
		else 
			if ( ngay == 7 || ngay == 8)
			{
				tien = 400000 * soGio;
				cout << "So tien: " << tien;
			}
	}
	else 
		if (ngay >= 2 && ngay <= 6)
		{
			if (thoiDiem >= 10 && thoiDiem <= 18)
			{
				tien = 80000 * soGio;
				cout << "So tien: " << tien;
			}
			else
				if (thoiDiem > 18)
				{
					tien = 200000 * soGio;
					cout << "So tien: " << tien;
				}
		}
		else
			if (ngay == 7 || ngay == 8)
				{
					tien = 200000 * soGio;
					cout << "So tien: " << tien;
