def gioi_thieu_ban_than():
    ten = "Bùi Minh Hiếu"
    nam sinh = 2004
    nghe_nghiep = "Sinh viên"
    so_thich = ["làm Toán", "chơi game", "du lịch"]

    print("Xin chào! Tôi tên là", ten)
    print("Tôi", tuoi, "tuổi và hiện đang làm việc với vai trò", nghe_nghiep + ".")
    print("Sở thích của tôi là:")
    for st in so_thich:
        print("- " + st)

gioi_thieu_ban_than()
