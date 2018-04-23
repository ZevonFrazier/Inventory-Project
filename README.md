# Inventory-Project
class Migration(migrations.Migration):
+
+    dependencies = [
+        ('company', '0002_auto_20180422_1201'),
+    ]
+
+    operations = [
+        migrations.AlterField(
+            model_name='company',
+            name='is_supplier',
+            field=models.BooleanField(default=True),
+        ),
+        migrations.AlterField(
+            model_name='company',
+            name='name',
+            field=models.CharField(help_text='Company name', max_length=100, unique=True),
+        ),
+    ]
