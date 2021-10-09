# hacktoberfest
participate in hactoberfest 2021 python accepted easy pull request merge
# Time:  O(m * n)
# Space: O(m + n)
# Using built-in bignum solution.
class Solution2(object):
    def multiply(self, num1, num2):
        """
        :type num1: str
        :type num2: str
        :rtype: str
        """
        return str(int(num1) * int(num2))
