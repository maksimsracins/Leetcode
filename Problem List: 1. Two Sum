/// <summary>
/// Given an array of integers nums and an integer target, return indices of the two numbers such that they add up to target.
///You may assume that each input would have exactly one solution, and you may not use the same element twice.
///You can return the answer in any order.
/// </summary>

public class Program
{

    public static void Main(string[] args)
    {
        var input = new int[] { 2, 0, 3, 7, 15 };
        var result = TwoSum(input, 9);
        foreach (var item in result)
        {
            Console.WriteLine(item);
        }
    }

    public static int[] TwoSum(int[] nums, int target)
    {
        int temp, temp2;
        for (int i = 0; i <= nums.Length - 1; i++)
        {
            temp = nums[i];
            for (int j = i + 1; j <= nums.Length - 1; j++)
            {
                temp2 = nums[j];
                if (target == temp + temp2)
                {
                    return new int[] { i, j };
                }
            }
        }
        return new int[] { 0, 0 };
    }
}
