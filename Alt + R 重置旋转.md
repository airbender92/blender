

要让你的对象平行于 **XY 平面** 并垂直于 **Z 轴**，你可以通过以下步骤来正确调整：

### 步骤：

1. **选择对象**：
   - 在 3D 视图中，右键或左键点击选中你想要调整的对象。

2. **进入对象模式**：
   - 确保你在 **Object Mode**（对象模式）下进行操作。如果不在对象模式，按 `Tab` 键切换。

3. **重置旋转**：
   - 按 `Alt + R` 来 **清除旋转**，将对象的旋转重置为零。这样它会恢复到没有旋转的默认状态。

4. **调整旋转**：
   - 你也可以手动设置对象的旋转角度来确保它平行于 **XY 平面**：
     - 选择对象后，在右侧的 **属性面板**（按 `N` 打开）中找到 **Transform** 面板。
     - 在 **Rotation** 部分，将 **X 和 Y** 轴的旋转值设置为 **0**，保持 **Z 轴的旋转**（如果需要）。
       - **X = 0**
       - **Y = 0**
       - **Z = 0**（如果对象已经旋转过，可能需要调整）。

5. **对齐到轴**：
   - 如果你希望将对象的 **Z 轴** 垂直于 **XY 平面**，可以使用 **对齐操作**：
     - 在顶部菜单栏选择 **Object > Transform > Align to Transform Orientations**，并确保选择 **Global**（全球坐标系），然后选择你要对齐的轴（Z 轴）。

6. **手动旋转**：
   - 如果你的对象没有完全垂直于 **Z 轴**，你可以手动调整旋转：
     - 选择对象后，在 **Transform** 面板中修改 **Rotation** 的 **X** 和 **Y** 值，直到对象平行于 **XY 平面**。

---

### **总结**
- 按 `Alt + R` 重置旋转，将对象的旋转清除为零。
- 通过手动调整 **X** 和 **Y** 轴的旋转角度，可以确保对象平行于 **XY 平面**。
