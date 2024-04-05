## Description

- Given an integer array `nums`, move all `0`'s to the end of it while maintaining the relative order of the non-zero elements.

- **Note** that you must do this **in-place** without making a copy of the array.
  > _Mani: Il faut utiliser le même tableau_

### Example 1:

Input: `nums = [0,1,0,3,12]`<br>
Output: `[1,3,12,0,0]`

### Example 2:

Input: `nums = [0]`<br>
Output: `[0]`

### Constraints:

- `1 <= nums.length <= 10**4`

- `-2**31 <= nums[i] <= 2**31 - 1`

> _Mani: Je crois qu'on peut ignorer les contraintes, et que c´est seulement pour nous indiquer les limites des tests. Du coup on a juste a utilisé des integers._

> _Rappel: `**` exprime la puissance_

Follow up: Could you minimize the total number of operations done?
