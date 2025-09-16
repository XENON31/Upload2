<?php
if (isset($_POST['folder'])) {
    $folder = $_POST['folder'];
    $folder_path = "files/" . $folder;
    
    if (is_dir($folder_path)) {
        $files = scandir($folder_path);
        $files = array_diff($files, array('.', '..'));
        
        if (count($files) > 0) {
            foreach ($files as $file) {
                $file_path = $folder_path . "/" . $file;
                $file_url = $file_path;
                $icon = get_file_icon($file);
                
                echo '<li class="file-item">';
                echo '<span><i class="fas ' . $icon . ' file-icon"></i> ' . $file . '</span>';
                echo '<a href="' . $file_url . '" class="download-btn" download><i class="fas fa-download me-1"></i> تحميل</a>';
                echo '</li>';
            }
        } else {
            echo '<li class="text-center">لا توجد ملفات في هذا المجلد</li>';
        }
    } else {
        echo '<li class="text-center text-danger">المجلد غير موجود</li>';
    }
} else {
    echo '<li class="text-center text-danger">لم يتم تحديد مجلد</li>';
}

function get_file_icon($filename) {
    $extension = pathinfo($filename, PATHINFO_EXTENSION);
    
    switch ($extension) {
        case 'pdf':
            return 'fa-file-pdf';
        case 'doc':
        case 'docx':
            return 'fa-file-word';
        case 'xls':
        case 'xlsx':
            return 'fa-file-excel';
        case 'ppt':
        case 'pptx':
            return 'fa-file-powerpoint';
        case 'zip':
        case 'rar':
            return 'fa-file-archive';
        case 'jpg':
        case 'jpeg':
        case 'png':
        case 'gif':
            return 'fa-file-image';
        default:
            return 'fa-file';
    }
}
?>