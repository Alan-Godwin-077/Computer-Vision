import cv2
import os

path = r"D:\Python\sample.jpg"

print("File exists:", os.path.exists(path))

image = cv2.imread(path)

if image is None:
    print("Python still cannot load the image.")
else:
    gray_image = cv2.cvtColor(image, cv2.COLOR_BGR2GRAY)
    cv2.imshow("Original Image", image)
    cv2.imshow("Grayscale Image", gray_image)
    cv2.waitKey(0)
    cv2.destroyAllWindows()
