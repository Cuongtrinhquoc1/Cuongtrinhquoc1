tên: Cache
  sử dụng: hành động/bộ nhớ đệm@v4.1.1
  với:
    # Danh sách các tệp, thư mục và mẫu ký tự đại diện để lưu vào bộ nhớ đệm và khôi phục
    con đường:
    # Một khóa rõ ràng để khôi phục và lưu bộ nhớ đệm
    chìa khóa:
    # Chuỗi nhiều dòng được sắp xếp liệt kê các khóa khớp tiền tố, được sử dụng để khôi phục bộ nhớ đệm cũ nếu không có lần truy cập bộ nhớ đệm nào xảy ra đối với khóa. Lưu ý `cache-hit` trả về false trong trường hợp này.
    restore-keys: # tùy chọn
    # Kích thước khối được sử dụng để chia nhỏ các tệp lớn trong quá trình tải lên, tính bằng byte
    upload-chunk-size: # tùy chọn
    # Một boolean tùy chọn khi được bật, cho phép người chạy Windows lưu hoặc khôi phục bộ nhớ đệm có thể được khôi phục hoặc lưu tương ứng trên các nền tảng khác
    enableCrossOsArchive: # tùy chọn, mặc định là false
    # Thất bại quy trình làm việc nếu không tìm thấy mục nhập bộ nhớ đệm
    fail-on-cache-miss: # tùy chọn, mặc định là false
    # Kiểm tra xem mục nhập bộ đệm có tồn tại cho đầu vào đã cho (khóa, khôi phục khóa) mà không cần tải xuống bộ đệm hay không
    lookup-only: # tùy chọn, mặc định là false
    # Chạy bước đăng bài để lưu bộ nhớ đệm ngay cả khi bước khác trước đó không thành công
    save-always: # tùy chọn, mặc định là false
          const pokemonIndices = [#, #, #, #, #,];

pokemonIndices.forEach(chỉ số => {
    this.scene.gameData.starterData[chỉ mục] = {
        Khả năngAttr: 7,
        Candycount: 200,
        Eggmove: 15,
        tình bạn: 90,
        thụ độngAttr: 3,
        giá trịGiảm: 2
    };

    this.scene.gameData.dexData[chỉ mục] = {
        caughtAttr: 255n,
        các câu sau: [31, 31, 31, 31, 31, 31],
        seenAttr: 479n,
        caughtCount: 69,
        hatchedSố lượng: 69,
        seenCount: 69,
        natureAttr: 67108862
    };

    console.log(`Thuộc tính đã được cập nhật cho Pokémon ${index}.`);
});
