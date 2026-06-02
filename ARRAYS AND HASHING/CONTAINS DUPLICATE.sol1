# KĨ THUẬT VÉT CẠN ( BRUTE FORCE) - vòng lặp lồng nhau
# $$ SPACE COMPLEXITY : 0(1) : không tạo mảng mới hay cấu trúc dữ liệu nào
# $$ TIME COMPLEXITY : 0(N^2) -> THỜI GIAN CHẠY QUÁ LỚN 
# +>Tìm tổng bằng mục tiêu , +>tính toán khoảng cách hoặc giá trị chênh lệch ,+> đếm số lượng cặp thỏa mãn điều kiện
class Solution:
    
    def hasDuplicate(self, nums: List[int]) -> bool:
        # vòng lặp i : chọn phần tử mốc
        # range(len(nums)) : tạo 1 dãy index từ 0 -> n - 1
        for i in range(len(nums)):
            # vòng lặp j : chọn phần tử đối
            for j in range (i + 1 , len(nums)):
                if nums[i] == nums[i + 1]:
                    return True;
        return False;
