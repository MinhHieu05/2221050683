def gioi_thieu_ban_than():
    ten = "Nguyễn Văn A"
    tuoi = 25
    nghe_nghiep = "Lập trình viên"
    so_thich = ["đọc sách", "chơi game", "du lịch"]

    print("Xin chào! Tôi tên là", ten)
    print("Tôi", tuoi, "tuổi và hiện đang làm việc với vai trò", nghe_nghiep + ".")
    print("Sở thích của tôi là:")
    for st in so_thich:
        print("- " + st)

gioi_thieu_ban_than()
